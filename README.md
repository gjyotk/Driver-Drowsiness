# Driver-Drowsiness

## Table of Contents

- About
- Dataset used
- Libraries used
- Credits



## About

The Driver Drowsiness Detection System is designed to enhance road safety by using machine learning to alert drivers when they show signs of drowsiness or distraction. It is developed using Keras, a deep learning framework, and integrates with an in-car camera to continuously monitor the driver's condition during a trip. It is designed to promote road safety, reduce accidents caused by drowsy driving, and protect the well-being of both drivers and passengers. It adheres to privacy and ethical guidelines and aims to provide a non-invasive solution to alert drivers effectively.

Beeping noise produced if driver is found to be drowsy or inactive to alert them. The processing of the Video feed will be done using MicroPython on a kernel level. This will increase the processing speed drastically which will be helpful to prevent life-threatening situations. 
A faster and more efficient deployment of the algorithm will reduce processing power required and the time taken to analyse the data.


## About the dataset
The dataset used is Drowsiness Dataset (link) https://www.kaggle.com/datasets/dheerajperumandla/drowsiness-dataset. It has images labelled for the status of facial expressions like, open and close for eyes and yawn and no yawn for yawning. Four folders in total are available for the same.

Total no. of images: 2900

Images used for training: 1377

## Libraries used
- numpy: NumPy (Numerical Python) is a fundamental library in Python for numerical and mathematical operations. It provides support for large and multi-dimensional arrays.

- pandas: Pandas is a popular open-source data manipulation and analysis library for Python.

- matplotlib: Matplotlib is a widely used and highly customizable data visualization library for Python.

- cv2: It refers to the OpenCV (Open Source Computer Vision) library, which is a popular open-source computer vision and image processing library for Python, C++, and other programming language.

- sklearn/ scikitlearn: Scikit-learn, often referred to as sklearn, is a popular open-source machine learning library for Python. It provides a wide range of tools and functions for machine learning and data analysis tasks.

- tensorflow: It is an open-source machine learning framework. It is designed to facilitate the development of machine learning and deep learning models.

- tensorflow.keras: It is an integral part of TensorFlow, serving as the high-level neural network API for building, training, and deploying deep learning models.


## Approach


https://github.com/gjyotk/Driver-Drowsiness/assets/112189682/a5b25320-8b19-48c2-b0c8-318ddff48cc3





![Model Approach](https://github.com/gjyotk/Driver-Drowsiness/assets/112189682/e62bf516-efa6-48b3-8959-8408d475ca0a)




## Output Images


![Result: Graph](https://github.com/gjyotk/Driver-Drowsiness/assets/112189682/41391e3b-f562-49a6-b309-89bc7893c898)

<img width="558" alt="Model Scores" src="https://github.com/gjyotk/Driver-Drowsiness/assets/112189682/4f7a9ec7-2281-409c-a52c-f003bf3a0eb4">

## Model Scores

- epochs: 50
- mAP: 0.9659
- loss: 0.0967
- val_loss: 0.0807
- val_accuracy: 0.9706


## Market Potential
- Potential: Can save lives and drastically reduce road instances happening due to driver drowsiness and lethargy.
- Cost: It is cost effective, requiring just an initial investment for a pi-camera. 
- Time efficient: The processing will be done on a low-level so that it is much faster and highly scalable.
- IoT and Connectivity: With Internet of Things (IoT) and vehicle connectivity, it's easier to collect and analyze real-time data from in-car systems.











## Credits 
gurojaschadha
Palak-Kaushik
gjyotk
Harshita0412
