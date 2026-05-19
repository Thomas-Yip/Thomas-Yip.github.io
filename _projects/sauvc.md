---
layout: page
title: SAUVC 2025 Autonomous Underwater Vehicle (Year 3) 
description: AUV development for the Singapore AUV Challenge
img: assets/img/sauvc_proj_page.jpg
importance: 5
category: work
---

Developed an Autonomous Underwater Vehicle (AUV) within a tight one-month timeframe and passed the competition video qualification on the first attempt for HKUST.

I participated heavily in the algorithm and hardware design, which included placing the electronics in a waterproof housing for the first time. I also developed a new communication protocol between the AUV and the topside control station, utilizing a brand-new Pixhawk flight controller and an NVIDIA Jetson computer.

For my first AUV project, I designed a robust navigation algorithm for the qualification task that guides a robot through a gate and back to its starting point. Using computer vision, the algorithm tracks thick lines on the pool floor to reach the target. Once it registers a designated visual signal, it executes a U-turn and returns. By relying on deterministic image processing rather than machine learning, the system bypasses common vulnerabilities related to poor training data quality and environmental inconsistencies.

[Demo video](https://youtu.be/3SxfcRNckAY?si=4WhmB3yf-YzAmUZb)

**Skills Earned:** Rapid Development, Hardware Design, Computer vision  