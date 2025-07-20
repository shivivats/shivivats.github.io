---
name: SEAWARE
description: Semantic-aware View Prediction for 360° Videos at the 5G Edge. <em>IEEE ISM 2022.</em>
full-name: Semantic-aware View Prediction for 360° Videos at the 5G Edge
conference: 2022 IEEE International Symposium on Multimedia (ISM)
# month: December 2022
# date: 2022-12-01
image: /assets/images/publications/seaware.png
tools: [5G, Python, Webapp, Mobile, VR]
---

<div>
<h1> Semantic-aware View Prediction for 360-degree Videos at the 5G Edge </h1>
<p class="h5"> <strong>Vats, Shivi</strong> and Park, Jounsup and Nahrstedt, Klara and Zink, Michael and Sitaraman, Ramesh and Hellwagner, Hermann </p>
<p class="h5"> 2022 IEEE International Symposium on Multimedia (ISM) </p>
</div>

<p><br /><em>You can read the whole paper <a href="https://ieeexplore.ieee.org/abstract/document/10019680/">here</a>.</em></p>

## Background

This paper was the culmination of 1.5 years of work on the [5G Playground Carinthia - Use Case "Virtual Realities"](https://5gplayground.at/en/use-cases/). I started work as a Project Assistant at my University halfway through the project's duration. In my time there, I worked on a **Python webapp** using **Flask**, **Celery**, **Redis**, and **Passenger** to predict viewport for 360° videos in advance. The viewport algorithm utilised was SEAWARE, and my work involved porting the algorithm from **MATLAB** to Python using **NumPy** and **SciPy** and running the code in the webapp in real-time as the user watched the video. **NGINX** was utilised as the server to run the webapp on and stream the video through.

The other part of my work involved working on a DASH Android client for 360° videos. The work was tedious since there was minimal documentation available, but I reverse engineered the client's algorithm and made modifications such that the client would request for new tiles whenever the user's viewport changed and not only when a DASH segment ended. This ended up **reducing the motion-to-glass latency by up to 62%** compared to the regular streaming method.

Below is the architecture of the app I developed.

<div>
<img src="/assets/images/publications/seaware.png" class="img-fluid" alt="SEAWARE Architecture"/>
</div>
<div class="text-center">
    SEAWARE Architecture
</div>

## Abstract

*In a 5G testbed, we use 360° video streaming to test, measure, and demonstrate the 5G infrastructure, including the capabilities and challenges of edge computing support. Specifically, we use the SEAWARE (Semantic-Aware View Prediction) software system, originally described in [^1], at the edge of the 5G network to support a 360° video player (handling tiled videos) by view prediction. Originally, SEAWARE performs semanticanalysis of a 360° video on the media server, by extracting, e.g., important objects and events.*     
*This video semantic information is encoded in specific data structures and shared with the client in a DASH streaming framework. Making use of these data structures, the client/player can perform view prediction without in-depth, computationally expensive semantic video analysis.*    
*In this paper, the SEAWARE system was ported and adapted to run (partially) on the edge where it can be used to predict views and prefetch predicted segments/tiles in high quality in order to have them available close to the client when requested. The paper gives an overview of the 5G testbed, the overall architecture, and the implementation of SEAWARE at the edge server. Since an important goal of this work is to achieve low motion-toglass latencies, we developed and describe “tile postloading”, a technique that allows non-predicted tiles to be fetched in high quality into a segment already available in the player buffer.*     
*The performance of 360° tiled video playback on the 5G infrastructure is evaluated and presented. Current limitations of the 5G network in use and some challenges of DASH-based streaming and of edge-assisted viewport prediction under “realworld” constraints are pointed out; further, the performance benefits of tile postloading are disclosed.*

For more information, please read the paper [here](https://ieeexplore.ieee.org/abstract/document/10019680/).

[^1]: J. Park, M. Wu, K.-Y. Lee, B. Chen, K. Nahrstedt, M. Zink, and R. Sitaraman, “SEAWARE: Semantic Aware View Prediction System for 360-degree Video Streaming,” in Proc. IEEE Int.l Symposium on Multimedia (ISM), 2020, pp. 57–64.


<p class="text-center">
{% include elements/ending-button.html link="/academic-work" text="Back to Academic Work" %}
</p>