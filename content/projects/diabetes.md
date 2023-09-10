---
title: "Diabetes Prediction Model using Pima Dataset"
description: "Do you have diabetes??"
dateString: Jul 2020 - Oct 2020
draft: false
tags: ["Logistic Regression", "Flask", "HTML", "CSS"]
showToc: false
weight: 206
cover:
#   image: "projects/sebart-pro/cover.jpeg"
---

## Description

Developed an end-to-end Machine Learning model capable of predicting Diabetic diagnosis using attributes such as BMI(Body Mass Index), Glucose, etc. This model is integrated with the Front end to enhance its utility.

Relevant paper ”Diabetes Prediction using Logistic Regression” accepted and published in ‘2nd International WIESymp
2021.’ held in Nov 2021


### Introduction:
Healthcare, as the foundation of human wellbeing, has always strived for early detection and timely intervention. In light of the escalating global diabetes epidemic, there is an urgent need to harness technology to predict potential cases. This initiative, centered on the Pima dataset, seeks to predict diabetes onset by analyzing various patient parameters, tapping into the potential of advanced machine learning models.

### Objective:
Given the alarming rise in diabetes and the intricate interplay of numerous factors leading to its onset, technology could be a beacon of hope. The goals of this project include:

Precise prediction of diabetes based on a gamut of health metrics.
Streamlining healthcare resources towards high-risk individuals for preventive care.
Offering insights into potential diabetes trends, thereby aiding in large-scale health planning.
Analysis and Methodology:
Inputs: Core data under the lens comprises metrics like age, gender, glucose levels, BMI, insulin levels, and a history of gestation diabetes.

### Functional Requirements:
Knowledge Collection: Pool data related to the critical metrics from reliable sources.
Data Preprocessing: Refine and standardize the data, prepping it for the training phase.
Learning and Testing: Segregate the data into training and test sets, employing the former to train the machine learning models.
Modeling: Select and apply the most apt algorithms on the processed data.
Predicting: Deploy the trained algorithms to forecast potential diabetes cases in unexplored datasets.
Non-Functional Requirements:
The software needs to be intuitive, ensuring effortless interactions for the users. Emphasis also lies on its responsiveness, robustness, and the ability to efficiently function under heavy data loads.

### Training Modules:
Dataset: Much like the previous datasets such as Mushroom or Soyabean, this dataset undergoes a rigorous feature selection using advanced algorithms, zeroing in on features pivotal for classification. Among the multitude of parameters, metrics like glucose levels emerged as a dominant predictive factor.

Clustering: The approach adopted groups interrelated attributes, thereby enhancing the accuracy of the prediction framework. Given the breadth of data features, a multi-dimensional clustering model was deemed fit.

Testing: Ensuring the reliability and precision of predictions, the models were subjected to exhaustive testing rounds.

### Results and Observations:
Logistic Regression: 80.2% accuracy

### Conclusions and Recommendations:
The Diabetes Prediction System offers a groundbreaking solution to tackle the global diabetes menace. While the results are heartening, it's imperative to acknowledge the system's limitations. The horizon ahead beckons the incorporation of real-time data assimilation and increasingly refined prediction algorithms, promising timely intervention and improved patient outcomes.



[Visit the project on GitHub](https://github.com/mounikapadala11/Diabetes-Prediction-Model-using-Pima-Dataset)

<!-- I worked on this project single-handedly during the summer break following my freshman year at NIT- Trichy. **SEBART-Pro** is a robot that follows a ball while balancing on two wheels. It can also recognize traffic signs and act accordingly. It has two stepper motors for precise position control and used an **Arduino Nano** as the microcontroller. The robot senses the tilt using an **MPU-6050 (6-axis gyroscope and accelerometer)** and converts the values from these sensors into angles using a **Kalman Filter**. It uses the **PID control algorithm** to balance on two wheels and a simple **Convolutional Neural Network** is used to recognize traffic signs.

![](/projects/sebart-pro/img1.jpeg) -->
