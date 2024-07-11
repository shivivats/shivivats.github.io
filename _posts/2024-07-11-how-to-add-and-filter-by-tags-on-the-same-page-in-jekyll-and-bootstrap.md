---
title: How to filter by tags on the same page in Jekyll using Bootstrap 5
tags: [Jekyll, Liquid, Bootstrap]
style: fill
category: Web Dev
text: light
description: Using Bootstrap 5 collapse classes and JavaScript functionality to dynamically change the page content based on the tag button clicked.
---

## The Problem

After years of bouncing between different themes, I finally settled on [PortfolYOU](https://github.com/YoussefRaafatNasry/portfolYOU) for my personal portfolio and blog. It's practically the theme of my dreams, but I wanted to go beyond simple aesthetics and implement some functional improvements.

My first big project was adding dynamic buttons to my project pages, heavily inspired by the portfolio of [11BelowStudio](https://11belowstudio.github.io/#/game-projects) (another fantastic theme option, by the way). Instead of using Jekyll's traditional approach of separate tag and category pages, I aimed to allow visitors to click on tag buttons directly on the project page and have the content dynamically update to display only the project cards belonging to that specific tag.

This post outlines the steps I took to achieve this functionality, as demonstrated on my [games](/projects/), [academic work](/academic-work/), and [other work](/other-work/) pages.

Please note: you may need to adjust the code slightly to ensure compatibility with your Jekyll and Liquid website.

## The Solution

### 1. Gathering and Organizing Tags

```liquid
{% raw %}
{%- assign tags = blank -%}
{%- for project in site.projects -%}
{%- assign project_tags = project.tags | join:'|' | append:'|' -%}
{%- if project_tags != '|' -%}
{%- assign tags = tags | append:project_tags -%}
{%- endif -%}
{%- endfor -%}
{%- assign tags = tags | split:'|' | uniq | sort -%}
{% endraw %}
```

First, we'll collect all the tags from your project collection. In this example, we'll assume you're using `site.projects`.

1. **Iterate through Projects**: Loop through each project in the `site.projects` collection.
2. **Extract Tags**: For each project, retrieve its associated tags.
3. **Create Tag String**: Append all project tags into a single string, separated by a pipe symbol (`|`).
4. **Split into Array**: Finally, split the tag string into an array and sort it alphabetically.

### 2. Displaying Tags as Buttons

```liquid
{% raw %}
<h3>Tags</h3>
<button type="button" class="btn btn-primary" aria-expanded="false" id="buttonAll" onClick="showAllCards()">All</button>
{% for tag in tags %}
<button type="button" class="btn btn-primary" aria-expanded="false" id="{{ 'button' | append: tag | slugify }}" onClick="collapseCardsForThisButton(this)">{{ tag }}</button>
{% endfor %}
{% endraw %}
```

We'll create individual buttons for each tag, allowing visitors to filter projects.

1. **Loop through Tags**: Iterate through the sorted tag array.

2. **Render Buttons**: For each tag, generate a button element. Remember to add the appropriate `onClick` functions to your elements.

A few items to note here:

- **JavaScript Control**: We'll use JavaScript functions instead of classes Bootstrap's collapse functionality for finer control over project visibility. Imagine a "Game G" with tags "A" and "B". Upon clicking tag A, game G will be among the list of games displayed. However, upon clicking tag B, game G will be hidden, since Bootstrap's functionality with classes only supports toggling. With JavaScript, we can ensure that projects with both tags remain visible.

- **Button IDs**: We'll use IDs formatted like `button-tag` to easily identify the associated tag with each button.

- **"All" Button**: We'll include an "All" button to display all projects.

### 3. Dynamically Filtering Projects

Here's where we use Bootstrap and Javascript to filter projects based on clicked tags.

1. **JavaScript Functions**: Write JavaScript functions to utilize Bootstrap's collapse functionality. We'll add or remove the show class from elements instead of using the collapse function to avoid animations.

2. **Project Card Classes**: Add classes like `collapse-tag`` to project cards based on their tags. This allows our JavaScript functions to target and show/hide the correct cards.


```javascript
<script>
    function showAllCards() {
        const collapseElementList = document.querySelectorAll('.collapse')
        const collapseList = [...collapseElementList].map(collapseEl => {
            if (!$(collapseEl).hasClass('show')) {
                $(collapseEl).addClass('show')
            }
        })
    }

    function hideAllCards() {
        const collapseElementList = document.querySelectorAll('.collapse.show')
        const collapseList = [...collapseElementList].map(collapseEl => $(collapseEl).removeClass('show'))
    }

    function collapseCardsForThisButton(element) {
        hideAllCards()
        const collapseElementList = document.querySelectorAll('.collapse' + element.id.substring(6))
        const collapseList = [...collapseElementList].map(collapseEl => new bootstrap.Collapse(collapseEl))
    }
</script>
```

```liquid
{% raw %}
<div class="{% for tag in project.tags %} {{'collapse' | append: tag | slugify | append: ' '}} {% endfor %} collapse show ....">
{% endraw %}
```

## The Result

<img src="/assets/images/posts/dynamic-tags.gif" />

That's it! With these steps, your project page will now feature a dynamic tag filtering system, allowing visitors to easily browse your work by category.

If you'd like to, you can check out more of my [web dev writing](/blog/categories/#web-dev), or just the rest of [my blog](/blog/). 

{% include looking-for-job.html %}

Thanks for reading!

## References

These posts helped me get some inspiration, but in the end I ended up reverse-engineering the already existing tags page in this theme and referred to the Bootstrap 5 docs for the styling.

- [Jekyll Tags on Github Pages](http://longqian.me/2017/02/09/github-jekyll-tag/)
- [How to display tags in jekyll and get the tag to click through to all relevant collection posts - Stack Overflow](https://stackoverflow.com/questions/54769586/how-to-display-tags-in-jekyll-and-get-the-tag-to-click-through-to-all-relevant-c)
- [Bootstrap 5 Collapse](https://getbootstrap.com/docs/5.3/components/collapse/)
- [Bootstrap 5 Buttons](https://getbootstrap.com/docs/5.3/components/buttons/)