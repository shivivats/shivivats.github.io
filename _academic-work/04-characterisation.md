---
name: Characterization of QoE of PCs
description: Characterization of the Quality of Experience and Immersion of Point Cloud Video Sequences through a Subjective Study. <em>IEEE Access 2023.</em>
full-name: Characterization of the Quality of Experience and Immersion of Point Cloud Video Sequences through a Subjective Study
conference: 2023 IEEE Access Volume 11
# month: October 2023
# date: 2023-10-01
image: /assets/images/publications/characterisation.png
tools: [AR, HoloLens, QoE, Unity, C#]
---

<div>
<h1> Characterization of the Quality of Experience and Immersion of Point Cloud Video Sequences through a Subjective Study </h1>
<p class="h5"> Nguyen, Minh and <strong>Vats, Shivi</strong> and Van Damme, Sam and Van der Hooft, Jeroen and Vega, Maria Torres and Wauters, Tim and De Turck, Filip and Timmerer, Christian and Hellwagner, Hermann </p>
<p class="h5"> 2023 IEEE Access Volume 11 </p>
</div>

<p><br /><em>You can read the whole paper <a href="https://ieeexplore.ieee.org/abstract/document/10288458/">here</a>.</em></p>

## Background

This is a journal paper, part of our work with the [SPIRIT Project](https://www.spirit-project.eu/), expanding on [our first study](/academic-work/06-impact) with point clouds. For this work, we tested various Quality of Experience (QoE) models using the data obtained in the study. The results are compiled and the impact of various factors on the QoE of PCs is discussed. The data can be found on GitHub at [minhkstn/QoE-and-Immersion-of-Dynamic-Point-Cloud](https://github.com/minhkstn/QoE-and-Immersion-of-Dynamic-Point-Cloud).

<div>
<img src="/assets/images/publications/characterisation.png" class="w-50" alt="Our MOS vs objective color PSNR at a 5 meter viewing distance"/>
</div>
<div class="text-center">
    Our MOS vs objective color PSNR at a 5 meter viewing distance
</div>

## Abstract

*Point cloud streaming has recently attracted research attention as it has the potential to provide six degrees of freedom movement, which is essential for truly immersive media. The transmission of point clouds requires high-bandwidth connections, and adaptive streaming is a promising solution to cope with fluctuating bandwidth conditions. Thus, understanding the impact of different factors in adaptive streaming on the Quality of Experience (QoE) becomes fundamental. Point clouds have been evaluated in Virtual Reality (VR), where viewers are completely immersed in a virtual environment. Augmented Reality (AR) is a novel technology and has recently become popular, yet quality evaluations of point clouds in AR environments are still limited to static images. In this paper, we perform a subjective study of four impact factors on the QoE of point cloud video sequences in AR conditions, including encoding parameters (quantization parameters, QPs), quality switches, viewing distance, and content characteristics. The experimental results show that these factors significantly impact the QoE. The QoE decreases if the sequence is encoded at high QPs and/or switches to lower quality and/or is viewed at a shorter distance, and vice versa. Additionally, the results indicate that the end user is not able to distinguish the quality differences between two quality levels at a specific (high) viewing distance. An intermediate-quality point cloud encoded at geometry QP (G-QP) 24 and texture QP (T-QP) 32 and viewed at 2.5m can have a QoE (i.e., score 6.5 out of 10) comparable to a high-quality point cloud encoded at 16 and 22 for G-QP and T-QP, respectively, and viewed at a distance of 5 m. Regarding content characteristics, objects with lower contrast can yield better quality scores. Participants’ responses reveal that the visual quality of point clouds has not yet reached an immersion level as desired. The average QoE of the highest visual quality is less than 8 out of 10. There is also a good correlation between objective metrics (e.g., color Peak Signal-to-Noise Ratio (PSNR) and geometry PSNR) and the QoE score. Especially the Pearson correlation coefficients of color PSNR is 0.84. Finally, we found that machine learning models are able to accurately predict the QoE of point clouds in AR environments.*

For more information, please read the paper [here](https://ieeexplore.ieee.org/abstract/document/10288458/).


<p class="text-center">
{% include elements/button.html link="/academic-work" text="Back to Academic Work" %}
</p>