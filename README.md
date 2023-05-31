# Bangkit-Machine Learning

## Image Classification
The models aims to classify images of ornamental plants into different categories using the TensorFlow library and the EfficientNetB3 model. The EfficientNetB3 is a state-of-the-art convolutional neural network architecture known for its efficiency and strong performance in image classification tasks.

## Dataset
The model is trained using the training dataset while being evaluated using validation dataset to check if there's overfitting or underfitting in the model. After training, the model is evaluated using the test dataset to measure its performance in classifying ornamental plants. The dataset previously has been split into training, validation, and test with ratio (0.7,0.15,0.15)

| Training | Validation | Test |
|----------|----------|----------|
| 1333   | 310   | 294   |

As of now, there were 8 ornamental plant class in the dataset:
- Agglonema
- Alocasia
- Gelombang Cinta
- Monstrea
- Lidah Mertua
- Lili Paris
- Pucuk Merah
- Suplir

## Modelling Flowchart
![Alt Text](https://github.com/ornaman-dev/Bangkit-MachineLearning/blob/Image-Classification/Assets/MLflow.png)

## Evaluation Result
### Accuracy Comparasion

![Alt Text](https://github.com/ornaman-dev/Bangkit-MachineLearning/blob/Image-Classification/Assets/model_comparasion_accuracy.png)

### Learning Plot

![Alt Text](https://github.com/ornaman-dev/Bangkit-MachineLearning/blob/Image-Classification/Assets/Learning_Plot_EfficientNetB3.png)

### Confusion Matrix

![Alt Text](https://github.com/ornaman-dev/Bangkit-MachineLearning/blob/Image-Classification/Assets/ConfusionMatrix.png)

## Getting Started
Preview the prediction through streamlit
### Prerequisites
- Install the requirements
```
pip install -r /path/to/requirements.txt
```

### Installation
1. Change directory
```
cd Bangkit-MachineLearning
```
2. Open terminal
```
streamlit run app.py
```
### Usage
![Alt Text](https://github.com/ornaman-dev/Bangkit-MachineLearning/blob/Image-Classification/Assets/demo.gif)

### Link Preview
<a href = 'https://alexanderjanuar-bangkit-machinelearning-app-image-classi-ciqo1j.streamlit.app/' target="_blank">Click Here</a>

