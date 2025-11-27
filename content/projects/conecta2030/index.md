---
title: Conecta2030
date: 2023-10-26
links:
  - type: site
    url: https://lasid.dcomp.ufscar.br/conecta-2030/
tags:
  - Computer vision
---

I was a member of [Conecta2030](https://lasid.dcomp.ufscar.br/conecta-2030/), a project where 5G, Cellular Vehicle-to-Everything, digital twins, and artificial intelligence will be used in connection to detect risky situations involving vulnerable road users (VRUs), such as pedestrians, cyclists and motorcyclists. The project has multidisciplinary teams from different universities: Federal University of São Carlos (UFSCar), São Paulo University (USP), Institute of Research of Centro Universitário Facens (IP FACENS), and Germany’s Technische Hochschule Ingolstadt (THI). The project also received collaborations from TIM Brasil and Stellantis. Worth highlighting that this project was approved in the [Rota 2030 Program](https://mover.fundep.ufmg.br/home/).

As a member of the AI team, I mainly developed 3D perception models. I trained SECOND and BEVFusion models in simulated and real infrastructure (roadside) view datasets. Besides that, I implemented the 3D tracking and trajectory prediction model, coupling it with the MMDetection3D library, creating a framework that detects, tracks, and predicts trajectories, which was used in the final project infrastructure. I also modified the simulated DOLPHINS dataset for our scenario, adding VRU objects for cyclists and motorcyclists, and tracking IDs for tracking and trajectory evaluation. Finally, I generated some risky simulated scenarios using CARLA, which were used to evaluate our models through different LiDAR sensors.

<!--more-->
