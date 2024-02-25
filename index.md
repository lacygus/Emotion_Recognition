# Enhancing Emotion Recognition in AI: A CLIP-Dissect Approach

## Section B01: Robust and Interpretable Neural Network Models for Computer Vision and Natural Language Processing
### Joon Cha, Sungjin Choi, Jasmine Lo, Hieu Luu
### Mentor: Lily Weng

## Introduction
Our project looks at how interpreting neural networks can make image emotion recognition systems better. Currently, the best method to classify emotions based on an image is with deep learning, a rapidly growing field with state of the art performance in visual tasks. However, it is unclear what is happening within deep learning models that leads to such strong performance, often being nicknamed a “black box.”  With the development of CLIP-Dissect, which is a tool to easily interpret the role of deep neural network neurons, we seek to use it to understand how a model classifies emotions, what biases there are, and how to improve it

## Data
    
- FER2013
  - Description: The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centered and occupies about the same amount of space in each image.
  - Task: Categorize each face based on the emotion shown in the facial expression into
  one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral).
  - Training Set: 28,709 examples.
  - Public Test Set: 3,589 examples.
  - Link: [FER2013](https://www.kaggle.com/datasets/msambare/fer2013)

## Methods
In our project, we employed a comprehensive approach to understand and interpret facial expressions through machine learning models, focusing on the Facial Expression Recognition 2013 (FER-2013) dataset. The methodology involved several key steps, beginning with the conversion of existing models to formats compatible with advanced analysis tools such as PyTorch and ONNX. This allowed for the seamless integration of models with interpretability techniques like CLIP-Dissect and Concept-Based Model (CBM) analysis.

## Results

## Discussion

## Conclusion

## References
