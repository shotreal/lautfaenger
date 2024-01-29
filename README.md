# Noise Pollution Visualization Project

![Project Banner](images/project_banner.png)

## Overview

This project focuses on visualizing noise pollution on a map, leveraging a combination of hardware and software components. The hardware includes a 3D-printed case housing an Arduino WROOM32 and a Max9814 microphone for sound recording and Fourier analysis. 
The plan is to upload the gathered data to a webserver, and visualizes it on a map using Python, InfluxDB, and Grafana.

## Importance of the Project

Noise pollution is a pervasive environmental issue with significant impacts on health and well-being. Understanding and mapping noise levels across different locations can help identify high-risk areas, inform urban planning, and guide policy decisions. 
This project aims to contribute to the awareness and management of noise pollution by providing a visual representation of sound data on a city map.

## Current State of Work

The hardware design, including the 3D-printed case, is complete and available in the "3D" subfolder. 
The arduino code to to record sound, perform Fourier analysis, and calculate noise levels per frequency band is work in progress. The next steps involves uploading this data to a webserver and visualizing it using InfluxDB and Grafana.

## 3D Model Renderings

### Case Rendering 01
<img src="https://github.com/shotreal/lautfaenger/blob/main/3D/Lautfaenger01.png" alt="Case 02" width="100%">


### Case Rendering 02
![Case 02](./3D/lautfaenger02.png)

### Case Rendering 03
![Case 03](./3D/lautfaenger03.png)
