---
layout: post
title: Multi-LiDAR Fusion with Translation and Rotation
subtitle: with Python, ROS-Noetic, Ubuntu
cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/multi_lidar_fusion_post/thumb.jpg
share-img: /assets/img/path.jpg
gh-repo: shoxa-mir/MultiLiDAR_Transform_Fusion
gh-badge: [star, fork, follow]
tags: [test]
comments: true
mathjax: true
author: Shokhrukh Miraliev
---

{: .box-success}
This repository provides a comprehensive framework for fusing data from multiple Lidar sensors while incorporating translations within the ROS (Robot Operating System) environment, specifically tailored for Ubuntu 20.04. Leveraging Python and ROS Noetic, this solution enables seamless integration and synchronization of data streams from multiple Lidar sensors, enhancing perception capabilities for robotics applications.

### LiDAR Hardware Setup
<table style="max-width: 100%;">
    <tr>
        <th>Top view</th>
        <th>Side view</th>
    </tr>
    <tr>
        <td style="width: 50%;"><img src="/assets/img/multi_lidar_fusion_post/fig1/truck_w_lidar_top.svg" style="width: 100%;"></td>
        <td style="width: 50%;"><img src="/assets/img/multi_lidar_fusion_post/fig1/truck_w_lidar_side.svg" style="width: 100%;"></td>
    </tr>
</table>

### LiDAR Range and FOV (Top)
<table style="max-width: 100%;">
    <tr>
        <th>Top view</th>
    </tr>
    <tr>
        <td style="width: 50%;"><img src="/assets/img/multi_lidar_fusion_post/fig2/truck_w_range_top.svg" style="width: 100%;"></td>
    </tr>
</table>

### LiDAR Range and FOV (Side)
<table style="max-width: 100%;">
    <tr>
        <th>Side view</th>
    </tr>
    <tr>
        <td style="width: 50%;"><img src="/assets/img/multi_lidar_fusion_post/fig2/truck_w_range_side.svg" style="width: 100%;"></td>
    </tr>
</table>


