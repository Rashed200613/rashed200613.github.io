---
layout: page
title: An Intelligent Video Surveillance System
description: Funded by UGC
img: assets/img/Accident_detection.png
importance: 1
category: Research
related_publications: True
---

## An Intelligent Video Surveillance System with Temporal-Enhanced YOLOv8 for Real-Time Fire, Accident, and License Plate Detection in Public Safety Monitoring

Real-time detection of safety-critical events such as fires, traffic accidents, and vehicle license plates is a key enabler for intelligent transportation and urban surveillance systems. In high-density CCTV networks, these tasks must be performed under diverse environmental conditions, including low light, motion blur, and compression artefacts, while meeting strict latency requirements. Conventional single-frame object detection methods often suffer from unstable predictions, producing false positives that can overwhelm monitoring operators and automated alert systems. To address these challenges, we propose a temporal-enhanced YOLOv8-based detection framework that explicitly incorporates temporal reasoning into the detection pipeline. Our approach combines histogram equalization for enhanced visual contrast, YOLOv8 for spatial detection, ByteTrack for robust object association, and a 1D Temporal Convolutional Network (1D-TCN) for temporal filtering of event predictions. This integration not only stabilizes detections across frames but also significantly reduces false alarms in continuous video streams. And dual-channel alert system, integrating multimedia notifications and voice calls, ensures a rapid response from stakeholders. Performance was evaluated against state-of-the-art methods, achieving an overall accuracy of 91.60%, surpassing techniques like color analysis with wavelet transform and YOLOv8-EfficientNetB0. With low latency (13.3 ms for fire, 11.4 ms for accidents) and high precision (94.4% for accidents, 95.4% for number plates), it excels in challenging conditions. This system contributes significantly to human well-being by enabling faster emergency response, enhancing public safety, and supporting smarter urban management.

## Publication

1. An Intelligent Video Surveillance System with Temporal-Enhanced YOLOv8 for Real-Time Fire, Accident, and License Plate Detection in Public Safety Monitoring. {% cite rashed2025fmlds %}
