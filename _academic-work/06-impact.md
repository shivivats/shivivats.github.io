---
name: Point Clouds QoE
description: Impact of Quality and Distance on the Perception of Point Clouds in Mixed Reality. <em>QoMEX 2023.</em>
image: /assets/images/publications/impact-of.png
tools: [AR, HoloLens, QoE, Unity, C#]
---

<div>
<h1> Impact of Quality and Distance on the Perception of Point Clouds in Mixed Reality </h1>
<p class="h5"> Nguyen, Minh and <strong>Vats, Shivi</strong> and Van Damme, Sam and Van Der Hooft, Jeroen and Vega, Maria Torres and Wauters, Tim and Timmerer, Christian and Hellwagner, Hermann </p>
<p class="h5"> 2023 15th International Conference on Quality of Multimedia Experience (QoMEX) </p>
</div>

## Background

This paper marked my first publication(s) with the [SPIRIT Project](https://www.spirit-project.eu/). The paper contains information about a subjective QoE study used to determine the impact of distance and quality on the perception of point clouds in Augmented (Mixed) Reality. The study was conducted using the Microsoft HoloLens 2 and involved asking 30+ participants to do the test and then performing statistical analysis on the compiled results. The dataset was also used to train a Quality of Experience model for Point Clouds in our extended abstract paper [here](/academic-work/05-no-reference).

This paper is one half of a two-part work, with the other half being a demo paper describing the testing platform used to conduct these experiments. I designed the testing platform alone, using **Unity**, **C#** and **Mixed Reality Toolkit (MRTK) 2** from Microsoft. The platform runs on the Microsoft **HoloLens 2** and is highly modular in terms of point clouds and testing parameters. You can read more about the platform [here](/academic-work/01-platform).

<div>
<img src="/assets/images/publications/impact-of.png" class="w-75" alt="Average QoE ratings of participants for task 1 in our experiments"/>
</div>
<div class="text-center">
    Glimpse into our results: average QoE ratings of participants for task 1 in our experiments
</div>

## Abstract

*Point Cloud (PC) streaming has recently attracted research attention as it has the potential to provide six degrees of freedom (6DoF), which is essential for truly immersive media. PCs require high-bandwidth connections, and adaptive streaming is a promising solution to cope with fluctuating bandwidth conditions. Thus, understanding the impact of different factors in adaptive streaming on the Quality of Experience (QoE) becomes fundamental. Mixed Reality (MR) is a novel technology and has recently become popular. However, quality evaluations of PCs in MR environments are still limited to static images.*
*In this paper, we perform a subjective study on four impact factors on the QoE of PC video sequences in MR conditions, including quality switches, viewing distance, and content characteristics. The experimental results show that these factors significantly impact QoE. The QoE decreases if the sequence switches to lower quality and/or is viewed at a shorter distance, and vice versa. Additionally, the end user might not distinguish the quality differences between two quality levels at a specific viewing distance. Regarding content characteristics, objects with lower contrast seem to provide better quality scores.*

For more information, please read the paper [here](https://ieeexplore.ieee.org/abstract/document/10178491/).


<p class="text-center">
{% include elements/button.html link="/academic-work" text="Back to Academic Work" %}
</p>