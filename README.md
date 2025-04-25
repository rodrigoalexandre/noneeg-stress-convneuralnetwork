[![License: MIT](https://img.shields.io/badge/License-MIT-brightgreen.svg)](https://opensource.org/licenses/MIT)
![GitHub language count](https://img.shields.io/github/languages/count/rodrigoalexandre/noneeg-stress-convneuralnetwork)
![GitHub top language](https://img.shields.io/github/languages/top/rodrigoalexandre/noneeg-stress-convneuralnetwork)
![GitHub Repo stars](https://img.shields.io/github/stars/rodrigoalexandre/noneeg-stress-convneuralnetwork)
## **DESCRIPTION**

Project developed for the study presented in the article *"A Convolutional Neural Network model for stress classification based on electrocardiogram data"* published by *International Journal of Scientific Research in Engineering and Management* (Volume 07, Issue 11, Nov. 2023). 

**Stress disorders** have aroused great interest among researchers and have been widely addressed in several studies due to the negative impacts they can cause to people's quality of life and the possibility of triggering serious illnesses that can seriously compromise physical health. Stress can be classified into three categories: cognitive stress (also called mental stress), emotional stress (also called affective stress), and physical stress. The **Electrocardiogram (ECG)** makes it possible to detect and classify stress disorders by analyzing the electrical activity of the heart.

This study proposes a **Convolutional Neural Network (CNN)** model for classification of stress through the analysis of ECG data. The model achieved a high accuracy in its predictions and presented an adequate balance between performance and computational costs.
<br><br>
## **PROJECT STRUCTURE**

|--- source<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- prepare-noneeg-dataset.ipynb (Python code to convert dataset original files to CSV)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- preprocess-noneeg-dataset.ipynb (Python code to performe the exploratory data analysis)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- knearestneighbors-model.ipynb (Python code to create and train a K-Nearest Neighbors model)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- randomforest-model.ipynb (Python code to create and train a random forest model)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- multilayerperceptron-model.ipynb (Python code to create and train a MLP model)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- conv-neuralnetwork-model.ipynb (Python code to create and train a CNN model)<br>
|--- dataset<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--- The dataset location
<br><br>
## **ARTICLE LINK**

https://doi.org/10.55041/IJSREM26771
<br><br>
## **RESOURCES**
The dataset used in this study is publicly available at: https://physionet.org/content/noneeg/1.0.0/
<br><br>
## **LICENSE**
This project is available under the **MIT license**. See the LICENSE file for more details.
<br><br>
