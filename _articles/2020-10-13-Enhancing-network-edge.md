---
title: "Dronenet-sim: A learning-based trace simulation framework for control networking in drone video analytics"
category: articles
permalink: /articles/2020-04-27-Design-of-trace-based-NS-3-simulations-for-UAS-video-analytics-with-geospatial-mobility/
excerpt: "Realistic UAV testbed building for developing novel network control algorithms relating to video streaming/analytics is time-consuming and difficult. Challenges arise when executing high-scale drone video analytics experiments due to: constraints in drone manufacturing, government regulation restrictions, and limited energy resources."
venue: "Proceedings of the 6th ACM Workshop on Micro Aerial Vehicle Networks, Systems, and Applications"
date: 2020-06-19
---

<a href="https://dl.acm.org/doi/abs/10.1145/3396864.3399705">Download PDF here</a>

Abstract: Unmanned Aerial Vehicles (UAVs) or drones equipped with cameras are extensively used in different applications for environmental situational awareness such as: smart agriculture, border security, intelligent transportation. Realistic UAV testbed building for developing novel network control algorithms relating to video streaming/analytics is time-consuming and difficult. Challenges arise when executing high-scale drone video analytics experiments due to: constraints in drone manufacturing, government regulation restrictions, and limited energy resources. Also, developing algorithms requires ability to understand impact of network protocol selection to handle diverse UAV mobility models as well as dynamic network status during edge-network video processing. In this paper, we propose a novel learning-based trace simulation framework viz. "DroneNet-Sim" that integrates simulation on both drone and networking sides. It allows for experimentation with network protocol selection (i.e., TCP/HTTP, UDP/RTP, QUIC) and video properties selection (i.e., codec, resolution) to ensure satisfactory video quality delivery in different drone flight scenarios. Using machine learning models, we show how DroneNet-Sim can process real-world drone traces that include various mobility models, geospatial link information and on-time network status obtained from real-world data-gathering efforts. Trace-based experiments with our DroneNet-Sim shows how video quality delivery (i.e., PSNR) using suitable control networking matches real-world measurements in terms of machine learning model accuracy.


Recommended citation: Qu, Chengyi, Alicia Esquivel Morel, Drew Dahlquist, and Prasad Calyam. "Dronenet-sim: A learning-based trace simulation framework for control networking in drone video analytics." In Proceedings of the 6th ACM Workshop on Micro Aerial Vehicle Networks, Systems, and Applications, pp. 1-6. 2020. 
