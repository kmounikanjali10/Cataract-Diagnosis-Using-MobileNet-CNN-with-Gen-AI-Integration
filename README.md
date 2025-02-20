# Cataract-Diagnosis-Using-MobileNet-CNN-with-Gen-AI-Integration

# Cataracts are a leading cause of vision loss globally. 

The goal is to develop a solution using MobileNet CNN to diagnose cataracts from eye images and integrating GenAI for user assistance.
Access to specialized healthcare is limited in many regions, leading to delays in diagnosis and treatment.


The model classifies eye images into two categories: "cataract" or "normal.“

# Dataset Description

Our dataset comprises a total of 860 fundus images named Ocular Disease Recognition sourced from Kaggle
The images show the rear eye part, including important components such as the macula, optic disc, retina, and blood vessels.

![image](https://github.com/user-attachments/assets/a4fa6fca-7538-443f-b3fd-34c5ea1f305a)

# Dataset Characteristics
Data Labeling :These images are divided into two classes: cataract (low, mild, severe) labelled as 0 and non-cataract labelled as 1 

Data Distribution: 
	Training set: 80% of the total dataset
	Validation set: 10% of the total dataset
	Testing set: 10% of the total dataset
 
Data Preprocessing techniques such as Data Augmentation, Image normalization, Data splitting

# Why MobileNet?
MobileNet is a type of Convolutional Neural Network (CNN) that is particularly well-suited for image recognition and processing tasks on mobile and embedded devices.

MobileNet was developed to address the limitations of traditional CNNs, which are often computationally expensive and require significant resources which uses depthwise separable convolutions to reduce the number of parameters and computational resources required.

![image](https://github.com/user-attachments/assets/5a47a805-2189-49fe-8d17-f75b195c8e18)

# Model Architecture Overview
The proposed model for cataract detection makes use of:
The base model (MobileNetV2)

Three convolutional layers with 64 filters, kernel size 3x3, and ReLU activation.

A global average pooling layer.

A flatten layer.

Four dense layers with ReLU activation, dropout, and L2 regularization.

![image](https://github.com/user-attachments/assets/3339ae82-4e8e-431c-ac24-66b9b1720360)

# Model Training
![image](https://github.com/user-attachments/assets/40915f0d-b6c4-40c5-955d-08b79236a19a)

# FASTAPI Framework
Fast API is a modern, fast (high-performance), web framework for building APIs It helps developers build applications quickly and efficiently.

Fast API is often used for building: APIs, Microservices, Real-time applications



# Integrating Gemini AI for User Clarification
Gemini AI is a cutting-edge artificial intelligence model

By integrating Gemini AI, systems can ask clarifying questions, refine user inputs.

To utilize the Gemini AI model for generating responses for user suggestions, we created and configured an API key that serves as an authentication mechanism

Users Can Ask Prompts Such As:

What are the available treatment options for cataracts?

How does the severity of cataracts affect my vision?

What does it mean if my diagnosis is categorized as 'Mild cataract'

![image](https://github.com/user-attachments/assets/46bd3ebb-da12-412b-b3d5-0dda9b8ca8b7)

# Output Demonstration

![image](https://github.com/user-attachments/assets/b90a6f88-1e9c-45dc-8429-8bcac77b3383)


![image](https://github.com/user-attachments/assets/fe3154a1-c8ed-4009-a6bf-3ba375fa93cc)


