# Awesome Driver Monitoring Systems [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A repo for the latest DMS databases &amp; papers. Feel free to contribute by creating issues or pull requests.

## Table of Contents

1. [Introduction](#introduction)
2. [Databases](#databases)
3. [Papers](#papers)
4. [Benchmarks](#benchmarks)

## Introduction

Driver monitoring systems (**DMS**) are an intelligent systems that monitor drivers with sensors (e.g., cameras and wearables) and determine whether to interfere with driving based on the data (e.g., images, videos, heart rates). More can be found on [Wikipedia](https://en.wikipedia.org/wiki/Driver_monitoring_system).

## Databases

### Vision-Based Datasets

| Dataset                                                                       | Year | Attributes                                           | No. of Drivers | Size | View                                             | Modality                               | Resolution          |
| ----------------------------------------------------------------------------- | ---- | ---------------------------------------------------- | -------------- | ---- | ------------------------------------------------ | -------------------------------------- | ------------------- |
| [StateFarm](https://www.kaggle.com/c/state-farm-distracted-driver-detection/) | 2016 | Distraction                                          | 26             | 22K  | Side                                             | RGB                                    | 640x480             |
| [NTHU-DDD](http://cv.cs.nthu.edu.tw/php/callforpaper/datasets/DDD/)           | 2016 | Drowsiness                                           | 36             | 210K | Front                                            | RGB + IR                               | 640x480             |
| [AUC-DD](https://abouelnaga.io/projects/auc-distracted-driver-dataset/)       | 2018 | Distraction                                          | 31             | 17K  | Side                                             | RGB                                    | 1920x1080           |
| [Drive&Act](https://driveandact.com/)                                         | 2019 | Distraction; Detection; Skeleton; Autonomous Driving | 15             | 12H  | Top (Front & Left & Right) + Front + Side + Back | RGB + Depth + IR + Skeleton + Interior | 1280x1024           |
| [DMD](https://dmd.vicomtech.org/)                                             | 2020 | Distraction; Detection; Drowsiness; Gaze             | 37             | 41H  | Top + Front + Side                               | RGB + Depth + IR                       | 1920x1080; 1280x720 |
| [3MDAD](https://sites.google.com/site/benkhalifaanouar1/6-datasets)           | 2020 | Distraction; Detection; Drowsiness; Day and Night    | 69             | 574K | Front + Side                                     | Day: RGB + Depth; Night: IR + Depth    | 640x480             |
| [DAD](https://github.com/okankop/Driver-Anomaly-Detection)                    | 2021 | Distraction; Open-Set Recognition                    | 31             | 13H  | Top + Side                                       | Depth + IR                             | 224x171             |

## Papers

To be finished...

## Benchmarks

To be finished...

## Acknowledgement

This repo is created with refereces to [:octocat: Awesome Crowd Counting](https://github.com/gjy3035/Awesome-Crowd-Counting) and [:octocat: Awesome Visual Transformer](https://github.com/dk-liang/Awesome-Visual-Transformer).
