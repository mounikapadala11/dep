---
title: " Agriculture Crop Yield Prediction Model"
description: "a system to predict the yield of the crop using Soil and Weather Parameters."
dateString: Jan 2019 - Mar 2019
draft: false
tags:
  [
    "Machine Learning",
    "Python",
    "Jupyter Notebook",
    "Support Vector Machine",
    "Random Forest",
    "Logistic Regression",
  ]
showToc: false
weight: 208
cover:
#   image: "projects/search-and-reconnaissance-robot/cover.jpeg"
---

## Description

Developed a system to predict the yield of the crop using Soil and Weather Parameters with an accuracy of 82 percent.

Implemented multiple models of Random Forest, SVM, and Logistic Regression, to improve the accuracy on held-out
data samples.

### Introduction:

Agriculture has always been the backbone of any civilization. With increasing urbanization and changing climatic patterns, ensuring optimal crop yield is becoming increasingly challenging. This project was undertaken to predict the yield of millet by analyzing various soil and weather parameters, and employing advanced machine learning techniques.

### Objective:

Given the complexities of modern agriculture, where a myriad of factors influence crop yields, there's a growing necessity to harness technology to aid farmers. This project aims at:

Accurately predicting the yield of millet based on various soil and weather conditions.
Optimizing resource allocation for maximizing crop yield and profits.
Assisting in forecasting agricultural yield, crop costs, and predicting rainfall patterns.
Analysis and Methodology:

Inputs: The primary data considered includes parameters like Moisture, Rainfall, Average Humidity, Mean/Max/Min Temperature, and soil types like alkaline, sandy, chalky, and clay.

### Functional Requirements:

Knowledge Collection: Accumulate data related to the relevant parameters from various sources.
Data Preprocessing: Clean and normalize the data to make it suitable for training machine learning models.
Learning and Testing: Split the data into training and test datasets and train the models using the training dataset.
Modeling: Choose and apply suitable algorithms to the preprocessed data.
Predicting: Use the trained models to predict the millet yield on new, unseen data.
Non-Functional Requirements: These are the qualities the software must possess, such as its responsiveness, safety, and ease of use. Other requirements include its scalability (e.g., its performance under the load of many concurrent users) and reliability.

### Training Modules:

Dataset: The dataset, similar to Mushroom or Soyabean, undergoes feature selection using the PSO-SVM algorithm to pick essential features based on which classification is done. Among various parameters, the use of fertilizers was found to have the highest predictive value.

Clustering: This method groups related attributes, ensuring a more accurate prediction model. For this project, a two-dimensional clustering approach was chosen due to the limited features in the dataset.

Testing: The models underwent rigorous testing to ensure the quality, accuracy, and reliability of predictions.

### Results and Observations:

Using advanced machine learning algorithms like Random Forest, SVM, and Logistic Regression, the system achieved varied levels of success:

Random Forest: 99.7% accuracy
SVM: 40.95% accuracy
Logistic Regression: 67.58% accuracy


### Conclusions and Recommendations:

The Crop Yield Prediction System provides an innovative solution to the challenges faced by modern agriculturists. While the system has proven its efficiency, it's important to note its limitations and the potential for further refinement. Future endeavors might incorporate real-time data analysis and even more precise prediction models, ensuring sustainable and optimized farming practices.




[Visit the project on GitHub](https://github.com/mounikapadala11/Agriculture-Crop-Yield-Prediction-Model)
<!-- 
About me old:

    Hi 👋, I'm Mounika, an [**MSc in Computer Scince**](https://cse.ucsd.edu/graduate/degree-programs/ms-program) student at the **University of California, San Diego**. I'm passionate about **Backend**, **Frontend**, **Networks** and **Machine Learning". I have experience in programming languages such as Python, C, C++ and web technologies like JavaScript, Flutter, HTML5, and CSS. I have also developed several projects and published papers in journals. Additionally, I have work experience as a software engineer and developer intern. I am interested in a career in software development and data science. As a technology enthusiast, I learn new techs in my free time. -->

<!-- Natural disasters like earthquakes and landslides are sudden events that cause widespread destruction and major collateral damage including loss of life. Though disasters can never be prevented, their effects on mankind can surely be reduced. In this paper, we present the design and control of SRR (Search and Reconnaissance Robot), a robot capable of traversing on all terrains and locating survivors stuck under the debris. This will assist the rescue team to focus on recovering the victims, leaving the locating task for the Robots. The unique features of the SRR above existing ATVs are active-articulation, modularity, and assisted-autonomy. Active-articulation allows the SRR to climb objects much tall than itself. Modularity allows the SRR to detach into smaller modules to enter tight spaces where the whole body can’t fit. Assisted-autonomy allows the SRR to detect the presence of objects in front and climb autonomously over them.

![](/projects/search-and-reconnaissance-robot/img1.jpeg)

![](/projects/search-and-reconnaissance-robot/img2.jpeg)

![](/projects/search-and-reconnaissance-robot/img3.jpeg) -->
