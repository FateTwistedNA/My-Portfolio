---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
# header:
#   og_image: "research/ecdf.png"
#sort:"order_number" 
---

My research mainly focuses on Person Re-Identification (Re-ID). This is a crucial task in computer vision that aims to identify individuals across different images or video frames. It plays a significant role in surveillance, security, and social media analysis. Person Re-ID aims to match images of the same person taken from different viewpoints, under varying lighting conditions, and across different time intervals. This task is complex due to factors like pose variations, occlusions, and changes in appearance.

![Person Re-ID baseline](/images/reid_baseline.jpg "Person Re-ID baseline")

Currently, I am developing models to tackle two challenging advanced subtasks in Person Re-ID namely **Cloth-changing Person Re-ID** and **Lifelong Person Re-ID**.

- **Cloth-changing Person Re-ID** specifically deals with the long-term scenario of identifying individuals who have changed their clothing, making it difficult to use traditional appearance-based models for recognition as appearance is no longer reliable. I am developing models that are able to capture clothing-invariant cues, such as body shape or gait.

![Cloth-changing Person Re-ID task](/images/ccreid.png "Cloth-changing Person Re-ID: matching the same person under cloth-changes from different views")

- **Lifelong Person Re-ID** addresses the scenario where the model needs to continuously adapt and improve its recognition capabilities as new data becomes available over time, ensuring reliable recognition even in dynamic and evolving environments. My works involve developing techniques that can efficiently perform well on new data without catastrophic forgetting and performance degradation.

![Lifelong Person Re-ID task](/images/lreid.png "Lifelong Person Re-ID: deal with incremental data without forgetting.")