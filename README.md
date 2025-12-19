## 🌦️ Weather Phenomenon Recognition (Image Classification)

### ✨ Introduction
Weather conditions play a critical role in areas such as transportation, agriculture, and public safety. Accurately identifying weather phenomena from images can support faster and more informed decision-making.

This project focuses on building an **image classification model** to recognise different types of weather phenomena using real-world image data. The goal is to classify images into five categories: **fog/smog, rain, rime, sandstorm, and snow**.

Through this project, I explored how deep learning can be applied to visual data and evaluated multiple model architectures to identify the most effective approach. This repository demonstrates my ability to work with image data, build neural networks, and translate technical results into meaningful insights.

---

### 📊 Dataset Overview
The dataset contains **2,726 real-world weather images**, organised into five folders corresponding to each weather condition:
- Fog / Smog  
- Rain  
- Rime  
- Sandstorm  
- Snow  

The images include varying lighting conditions, backgrounds, and levels of visual clarity, making the classification task realistic and challenging. The dataset was split into **70% training data** and **30% testing data** to ensure fair evaluation of model performance.

View **full analysis**: [here](https://github.com/Lexi-Nguyen/Weather-Phenomenon-Recognition/blob/b3fecbf9e0cb3b53c9588312ee1217eb0fd31cf1/Weather%20Phenomenon%20Recognition.ipynb)

---

### 🛠️ Tools & Technologies
- Python  
- Jupyter Notebook (.ipynb)  
- TensorFlow / Keras  
- NumPy & Pandas  
- Matplotlib & Seaborn  
- Google Colab (GPU-enabled environment)  

---

### 🔍 Project Workflow
This project followed a structured, end-to-end machine learning workflow:

#### Data Exploration & Preprocessing
- Loaded and visualised sample images  
- Resized images to a consistent format (128 × 128)  
- Normalised pixel values to improve model performance  
- Encoded labels for multi-class classification

<img width="536" height="515" alt="Image" src="https://github.com/user-attachments/assets/b3a23b28-9fb8-45e0-b4cc-17e4e05f5006" />

#### Model Development
- Built and tested multiple **Convolutional Neural Network (CNN)** architectures  
- Experimented with different numbers of layers, filters, and neurons  
- Applied batch normalisation and dropout to reduce overfitting  

#### Model Evaluation
- Compared models using training accuracy, testing accuracy, loss, and Kappa score
<img width="908" height="374" alt="Image" src="https://github.com/user-attachments/assets/8c05ffe9-d857-4353-9247-b4f360b73396" />
  
- Analysed confusion matrices to understand class-level performance  
- Identified strengths and weaknesses across different weather categories  

<img width="563" height="426" alt="Image" src="https://github.com/user-attachments/assets/92f2cd6b-a469-4028-89ec-de335fe942c6" />

<img width="528" height="305" alt="Image" src="https://github.com/user-attachments/assets/3a62dde7-2e4a-4247-be41-b0958b6f8d84" />

---

### 📈 Key Results
The best-performing model achieved:
- **Training accuracy:** ~89.7%  
- **Testing accuracy:** ~84.4%  
- **Kappa score:** 0.804  

Most weather categories were classified with strong accuracy. The **rime** category showed lower performance due to its visual similarity to other conditions such as fog and snow.

---

### 💡 Insights & Business Relevance
This project demonstrates how image-based AI models can support **weather monitoring agencies** by automating the recognition of weather conditions from visual data. The analysis highlights the importance of:
- High-quality and diverse training data  
- Comparing multiple models rather than relying on a single approach  
- Interpreting results beyond accuracy alone  

Further improvements could be achieved through additional data collection and experimenting with more advanced model architectures.

---

### 🌻 Hope this project is helpful and provides a clear overview of my approach to image-based weather classification.

