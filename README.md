# Automatic number plate recognition using deep learning

## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Installation](#installation)
  * [Deployment](#deployment)
  * [Technologies Used](#technologies-used)
  * [Team](#team)
  * [License](#license)

# Demo
![__results___25_0](https://user-images.githubusercontent.com/100205503/189724131-43c10507-7eb6-4dc8-b596-1fd1344daf8c.png)


# Overview 
Automatic License Plate Recognition (ALPR), As the name suggests, is a technology that uses the power of AI and deep learning to automatically detect and recognize the characters of a vehicle's license plate.
![Untitled](https://user-images.githubusercontent.com/100205503/189514680-2f7a55a2-d13a-4ec5-aa40-80df537a1873.jpg)
# Motivation
The drastic increase in the vehicular traffic on the roadways stimulates a huge demand in the technology for traffic monitoring and management. In this scenario, manual tracking of vehicles running fast on the road is practically not feasible. There will be wastage of man power and time. Even if it is operated manually, that will reflect huge difficulties and enormous errors. There are already available solutions for tracking the vehicles and number plates using machine learning algorithms. But in real time, these algorithms literally fail due to its complexity for processing in real time background. Hence there is an
instantaneous necessity to develop an automatic system that will help tracking the vehicles by tracing their number plates in a most efficient way.

This suggests an automated vehicle tracking system for the fast moving vehicles with the help of the surveillance cameras on the roadside could help solve the problem. The process of getting CCTV footage in the real time background is very tedious process. 
To cater to this problem,an efficient deep learning model such as this one is used for object detection.The proposed work consists of four main steps:
 1. In the first step, video footage is converted into images and the car is detected from each of the frames.
 2. License plate is detected from the detected cars. 
 3. The number plate characters reading are recognized from the detected number plates.

The proposed deep learning model uses ImageAI library to make the training process easier

# Data set Preparation
This is the data that was used ---


# Installation
The Code is written in Python 3.10
To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install lmageAI
```
```python
pip install lmageAI
```

# Deployment 

# Technologies Used
![](https://forthebadge.com/images/badges/made-with-python.svg)

![](https://www.google.com/imgres?imgurl=https%3A%2F%2Fjupyter.org%2Fassets%2Fshare.png&imgrefurl=https%3A%2F%2Fjupyter.org%2Ftry&tbnid=br6wrKbxgkz7rM&vet=12ahUKEwiIvtTg5-H5AhUSXxoKHbI8Ad4QMygIegUIARDMAQ..i&docid=M1b3uX4_0Stq-M&w=1200&h=630&q=python%20notebook%20svg&ved=2ahUKEwiIvtTg5-H5AhUSXxoKHbI8Ad4QMygIegUIARDMAQ)

Deep Laerning 
This system uses Convolutional Neural network(CNN) to detect the cars and number plate
This system also uses ImageAI library to make the process easier and also efficient.
It also uses several image processing techniques to preprocess the obtained frames. To annotate the images, an efficient annotation tool called Labeling is used. The whole system is implemented using python programming language.

![output-onlinepngtools (6)](https://user-images.githubusercontent.com/100205503/190846119-7a0f82e4-912d-4fd1-97f6-1aa1414ab996.png)

Tensorflow framework with the Keras deep learning library was also used for this project 

# Team
## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat-square)](#contributors)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

[Marble Kusanele Mpofu](https://github.com/kusanele/)

[Jean](https://github.com/jean-on-hub/)

# License
[![Apache license](https://img.shields.io/badge/license-apache-blue?style=for-the-badge&logo=appveyor)](http://www.apache.org/licenses/LICENSE-2.0e)


Copyright 2022 Marble Kusanele Mpofu

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0
