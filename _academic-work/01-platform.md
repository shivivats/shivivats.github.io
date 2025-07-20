---
name: Subjective Testing Platform
description: A Platform for Subjective Quality Assessment in Mixed Reality Environments. <em>QoMEX 2023.</em>
full-name: A Platform for Subjective Quality Assessment in Mixed Reality Environments
conference: 2023 15th International Conference on Quality of Multimedia Experience (QoMEX)
# month: June 2023
# date: 2023-06-01
image: /assets/images/publications/platform.jpg
tools: [AR, HoloLens, QoE, Unity, C#]
---

<div>
<h1> A Platform for Subjective Quality Assessment in Mixed Reality Environments </h1>
<p class="h5"> <strong>Vats, Shivi</strong> and Nguyen, Minh and Van Damme, Sam and van der Hooft, Jeroen and Vega, Maria Torres and Wauters, Tim and Timmerer, Christian and Hellwagner, Hermann </p>
<p class="h5"> 2023 15th International Conference on Quality of Multimedia Experience (QoMEX) </p>
</div>

<p><br /><em>You can read the whole paper <a href="https://ieeexplore.ieee.org/abstract/document/10178443/">here</a>.</em></p>

## Background

This work marked my first publication(s) with the [SPIRIT Project](https://www.spirit-project.eu/). The testing platform is developed for the Microsoft **HoloLens 2**  using **Unity**, **C#** and Microsoft's **Mixed Reality Toolkit (MRTK) 2**. I developed the whole platform myself.

The platform comprises two main functionalities: i. Point Cloud (PC) preview (pictured), and ii. Subjective Testing.

The PC preview functionality lets the user view up to 4 PCs and control them using the configuration menu. The PCs can be configured individually in their representation, quality level and distance from the user. This functionality is meant to be used as a way to showcase PCs and to test their perceived quality to get an idea of the configurations to use for the subjective tests.

The subjective testing functionality lets the user configure a test with any combination of PC representations, qualities, and distances that they like. The users are then able to run the test and the platform takes care of advancing the test and storing the participants' results in CSV files.

The users can import their own point clouds of choosing, in any qualities they like. The platform is highly modular.

*There have been more additions to the platform since, but they are not yet public.*

The platform was used to conduct a subjective study, which you can read more about [in this paper](/academic-work/06-impact).    
You can find the platform on GitHub [here](https://github.com/shivivats/MR-Subjective-Testing-Platform).

<div>
<img src="/assets/images/publications/platform.jpg" class="img-fluid" alt="The configuration panel of the testing platform depicting two point clouds in different representations"/>
</div>
<div class="text-center">
    The configuration panel of the testing platform depicting two point clouds in different representations
</div>

## Abstract

*3D objects are important components in Mixed Reality (MR) environments as they allow users to inspect and interact with them in a six degrees of freedom (6DoF) system. Point clouds (PCs) and meshes are two common 3D object representations that can be compressed to reduce the delivered data at the cost of quality degradation. In addition, as the end users can move around in 6DoF applications, the viewing distance can vary. Quality assessment is necessary to evaluate the impact of the compressed representation and viewing distance on the Quality of Experience (QoE) of end users. This paper presents a demonstrator for subjective quality assessment of dynamic PC and mesh objects under different conditions in MR environments. Our platform allows conducting subjective tests to evaluate various QoE influence factors, including encoding parameters, quality switching, viewing distance, and content characteristics, with configurable settings for these factors.*

For more information, please read the paper [here](https://ieeexplore.ieee.org/abstract/document/10178443/).


<p class="text-center">
{% include elements/ending-button.html link="/academic-work" text="Back to Academic Work" %}
</p>