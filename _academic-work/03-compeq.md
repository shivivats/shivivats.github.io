---
name: ComPEQ–MR
description: ComPEQ–MR&#58; Compressed Point Cloud Dataset with Eye Tracking and Quality Assessment in Mixed Reality. <em>ACM MMSys 2024.</em>
full-name: ComPEQ–MR&#58; Compressed Point Cloud Dataset with Eye Tracking and Quality Assessment in Mixed Reality
conference: 15th ACM Multimedia Systems (MMSys) Conference
month: April 2024
date: 2024-04-01
image: /assets/images/publications/compeq.png
tools: [AR, HoloLens, Eye Tracking, QoE, Unity, C#]
---

<div>
<h1> ComPEQ–MR: Compressed Point Cloud Dataset with Eye Tracking and Quality Assessment in Mixed Reality </h1>
<p class="h5"> Nguyen, Minh and <strong>Vats, Shivi</strong> and Zhou, Xuemei and Viola, Irene and Cesar, Pablo and Timmerer, Christian and Hellwagner, Hermann </p>
<p class="h5"> 15th ACM Multimedia Systems (MMSys) Conference </p>
</div>

<p><br /><em>You can read the whole paper <a href="https://dl.acm.org/doi/abs/10.1145/3625468.3652182">here</a>.</em></p>

## Background

This work is a continuation of [our initial work](/academic-work/06-impact) on subjective tests for Quality of Experience (QoE) for point clouds (PCs) as part of the [SPIRIT Project](https://www.spirit-project.eu/). We performed testing again, this time adding a task for the participants to simply move around and look at the point clouds. During this task, we gathered the participants eye tracking data, and generated heatmaps from it to get an idea of where the users prefer to look.

The subjective test was also different since this time we allowed the participants to move freely with 6DoF. The results were analysed and discussed in the paper.

Our [subjective testing platform](/academic-work/01-platform) was used to conduct these tests. I made modifications to the platform by adding fully configurable eye tracking tests to it, as can be seen in the figure below.

This data from these tests was made public for others to use in their research. It can be found at [ftp.itec.aau.at/datasets/ComPEQ-MR/](https://ftp.itec.aau.at/datasets/ComPEQ-MR/).

<div>
<img src="/assets/images/publications/compeq.png" class="img-fluid" alt="Platform architecture to conduct the subjective tests"/>
</div>
<div class="text-center">
    Platform architecture to conduct the subjective tests
</div>

## Abstract

*Point clouds (PCs) have attracted researchers and developers due to their ability to provide immersive experiences with six degrees of freedom (6DoF). However, there are still several open issues in understanding the Quality of Experience (QoE) and visual attention of end users while experiencing 6DoF volumetric videos. First, encoding and decoding point clouds require a significant amount of both time and computational resources. Second, QoE prediction models for dynamic point clouds in 6DoF have not yet been developed due to the lack of visual quality databases. Third, visual attention in 6DoF is hardly explored, which impedes research into more sophisticated approaches for adaptive streaming of dynamic point clouds.*    
*In this work, we provide an open-source Compressed Point cloud dataset with Eye-tracking and Quality assessment in Mixed Reality (ComPEQ–MR). The dataset comprises four compressed dynamic point clouds processed by Moving Picture Experts Group (MPEG) reference tools (i.e., VPCC and GPCC), each with 12 distortion levels. We also conducted subjective tests to assess the quality of the compressed point clouds with different levels of distortion. The rating scores are attached to ComPEQ–MR so that they can be used to develop QoE prediction models in the context of MR environments. Additionally, eye-tracking data for visual saliency is included in this dataset, which is necessary to predict where people look when watching 3D videos in MR experiences. We collected opinion scores and eye-tracking data from 41 participants, resulting in 2132 responses and 164 visual attention maps in total.*

For more information, please read the paper [here](https://dl.acm.org/doi/abs/10.1145/3625468.3652182).


<p class="text-center">
{% include elements/button.html link="/academic-work" text="Back to Academic Work" %}
</p>