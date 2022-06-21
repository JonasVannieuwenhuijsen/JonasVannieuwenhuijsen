---
author: "Jonas Vannieuwenhuijsen"
title: "Bachelor Thesis"
links:
  - title: Article Link
    description: Estimation of SpO2 and Heart Rate based on Photoplethysmographic Measurements at the Sternum.
    website: https://drive.google.com/file/d/1AvU1a8FEpvjBWtOLp0iJ-ixQmR8hXcha/view?usp=sharing
    image: https://fonts.gstatic.com/s/i/productlogos/drive_2020q4/v8/web-64dp/logo_drive_2020q4_color_2x_web_64dp.png
date: "2021-06-26"
description: "Estimation of SpO2 and Heart Rate based on Photoplethysmographic Measurements at the Sternum."
tags: [
    "Bachelor Thesis",
    "Photoplethysmography",
]
categories: [
    "school",
    "thesis",
]
image: "BachelorThesisFront.jpg"
---

## Abstract

Continuous observation of a patient's health parameters in the hospital is very important. Oxygen saturation and heart rate are two important health parameters to determine the early warning score. These 2 health parameters can be determined by using photoplethysmography (PPG). The PPG uses light of different wavelengths and a photodetector to capture the reflected light.

Raw data was obtained from 2 different devices. On the first device, 2 PPG sensors are present in a different location. This makes it possible to determine at which location the PPG sensor measures the best data. The data transfer is accomplished via a USB connection. In the second device, there is only 1 PPG sensor present and the data transfer is transferred via MQTT over Wi-Fi.

For the data analysis, little difference in data quality was observed between the raw data coming from both the devices. The raw data was filtered in MATLAB using a lowpass filter with a cutoff frequency of 1 Hz and an infinite impulse response (IIR). Then the data is processed in MATLAB to determine the heart rate and oxygen saturation values.

Tests were conducted on 4 healthy volunteers, and the extracted data has indicated that both the phi value and the heart rate are fairly stable. The next step is to determine the SpO2 level based on the phi value. Furthermore, the heart rate variability (HRV) and the respiration rate (RR) can be calculated.
Finally, when the case is correctly positioned with the correct settings for the LED intensity, a very nice signal is measured that ensures that we are able to obtain a good and stable result.
