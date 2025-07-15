---
name: No-Reference Quality of Experience Model for Dynamic Point Clouds in Augmented Reality
description: No-Reference Quality of Experience Model for Dynamic Point Clouds in Augmented Reality. <em>MHV 2024.</em>
full-name: No-Reference Quality of Experience Model for Dynamic Point Clouds in Augmented Reality
conference: 3rd Mile-High Video (MHV) Conference 2024
# month: February 2024
# date: 2024-02-01
image: /assets/images/publications/no-reference.png
tools: [QoE, Point Clouds]
---

<div>
<h1> No-Reference Quality of Experience Model for Dynamic Point Clouds in Augmented Reality </h1>
<p class="h5"> Nguyen, Minh and <strong>Vats, Shivi</strong> and Hellwagner, Hermann </p>
<p class="h5"> 3rd Mile-High Video (MHV) Conference 2024</p>
</div>

<p><br /><em>You can read the whole paper <a href="https://dl.acm.org/doi/abs/10.1145/3638036.3640248">here</a>.</em></p>

## Background

This paper is a short work containing a model for determining the Quality of Experience (QoE) of Point Clouds (PCs) in Augmented Reality. The model is a fine-tuned version of the ITU-T P.1203[^1] model trained using the dataset from [our previous work](/academic-work/06-impact). It is part of our work with the [SPIRIT Project](https://www.spirit-project.eu/).

You can find the model on GitHub at [minhkstn/itu-p1203-point-clouds](https://github.com/minhkstn/itu-p1203-point-clouds).

<div>
<img src="/assets/images/publications/no-reference.png" class="w-75" alt="Perceived vs predicted MOS for our fine-tuned P.1203 model"/>
</div>
<div class="text-center">
    Perceived vs predicted MOS for our fine-tuned P.1203 model
</div>

## Abstract

*Point cloud streaming is becoming increasingly popular due to its ability to provide six degrees of freedom (6DOF) for immersive media. Measuring the quality of experience (QoE) is essential to evaluate the performance of point cloud applications. However, most existing QoE models for point cloud streaming are complicated and/or not open source. Therefore, it is desirable to provide an opensource QoE model for point cloud streaming. [...]*

The abstract is cut short since the paper itself is an extended abstract. For more information, please read the paper [here](https://dl.acm.org/doi/abs/10.1145/3638036.3640248).


[^1]: ITU-T. [n. d.]. Rec. P.1203. Parametric bitstream-based quality assessment of progressive download and adaptive audiovisual streaming services over reliable transport - video quality estimation module. http://handle.itu.int/11.1002/ps/P1203-01

<p class="text-center">
{% include elements/button.html link="/academic-work" text="Back to Academic Work" %}
</p>