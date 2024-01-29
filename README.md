# Noise Pollution Visualization Project

## Overview

This project focuses on visualizing noise pollution on a map, leveraging a combination of hardware and software components. The hardware includes a 3D-printed case housing an Arduino WROOM32 and a Max9814 microphone for sound recording and Fourier analysis. 
The plan is to upload the gathered data to a webserver, and visualizes it on a map using Python, InfluxDB, and Grafana.

## Importance of the Project

Noise pollution is a pervasive environmental issue with significant impacts on health and well-being. Understanding and mapping noise levels across different locations can help identify high-risk areas, inform urban planning, and guide policy decisions. 
This project aims to contribute to the awareness and management of noise pollution by providing a visual representation of sound data on a city map.

## Current State of Work

The design for the 3D-printed case, is complete and available in the "3D" subfolder. 
The arduino code to to record sound, perform Fourier analysis, and calculate noise levels per frequency band is work in progress. After this is completed the next steps involves uploading this data to a webserver and visualizing it using InfluxDB and Grafana.

## Challenges
### Calibration
The sound levels produced by the AD converter somehow need to be matched to db otherwies they are pretty ueseless. The first apporach is to do this by using a soundMeter app on a smartphone and play sounds of different voluemes and frequencies. 
The readings of the app can then be used to calibrate.


## 3D Model Renderings

### Bottom view with cover
<img src="https://github.com/shotreal/lautfaenger/blob/main/3D/Lautfaenger01.png" alt="Bottom view with cover" width="100%">

### Bottom view without cover
<img src="https://github.com/shotreal/lautfaenger/blob/main/3D/Lautfaenger02.png" alt="Bottom view without cover" width="100%">

### Top view
<img src="https://github.com/shotreal/lautfaenger/blob/main/3D/Lautfaenger03.png" alt="Top view" width="100%">
