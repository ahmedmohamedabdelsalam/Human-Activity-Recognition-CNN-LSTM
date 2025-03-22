# Human Activity Recognition (HAR) using CNN-LSTM

## Project Overview
This project implements a deep learning solution for Human Activity Recognition (HAR) using a CNN-LSTM neural network architecture, trained on the UCI HAR Dataset.  
![Python](https://img.shields.io/badge/Python-3.8%2B-blue) ![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange) ![License](https://img.shields.io/badge/License-MIT-green)  

## Project Objectives
- Develop an advanced machine learning model for activity recognition  
- Classify human activities using smartphone sensor data  
- Demonstrate the effectiveness of CNN-LSTM architecture  

## Dataset  
### UCI Human Activity Recognition Dataset  
- **Source**: University of California, Irvine  
- **Activities**: 6 different human activities  
- **Total Samples**: 10,299  
- **Features**: 561 time and frequency domain variables  

### Recognized Activities  
1. Walking  
2. Walking Upstairs  
3. Walking Downstairs  
4. Sitting  
5. Standing  
6. Laying  

## Model Architecture  
### Key Components  
- Convolutional Layers (Feature Extraction)  
- LSTM Layers (Sequence Processing)  
- Dropout Regularization  
- Fully Connected Layers  

### Technical Specifications  
- **Model**: CNN-LSTM  
- **Input Shape**: (51, 11)  
- **Optimizer**: Adam  
- **Loss Function**: Categorical Crossentropy  

## Performance Metrics  
- **Accuracy**: 93.25%  
- **Precision**: 0.92  
- **Recall**: 0.93  
- **F1-Score**: 0.92  

## Installation  
### Prerequisites  
- Python 3.8+  
- TensorFlow 2.x  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

### Clone the Repository  
```bash
git clone https://github.com/ahmedmohamedabdelsalam/human-activity-recognition.git
cd human-activity-recognition
