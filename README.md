# Image Classification using MobileNetV2 and ResNet50V2

This project implements and compares two deep learning models, MobileNetV2 and ResNet50V2, for image classification tasks. The objective is to evaluate their performance, efficiency, and suitability under the same dataset and training conditions.

---

## Overview

The project focuses on:

- Building image classification pipelines using pretrained CNN architectures  
- Fine-tuning MobileNetV2 and ResNet50V2 models  
- Comparing lightweight vs deep residual networks  
- Evaluating model accuracy and performance  

Both models are trained and tested on the same dataset to ensure a fair comparison.

---

## Models Used

### MobileNetV2
- Lightweight architecture optimized for efficiency  
- Suitable for low-resource environments  
- Uses depthwise separable convolutions  

### ResNet50V2
- Deep residual network with skip connections  
- Handles vanishing gradient problem effectively  
- Higher computational cost but strong performance  

---

## Workflow

1. Data loading and preprocessing  
2. Image resizing and normalization  
3. Model initialization with pretrained weights  
4. Fine-tuning of top layers  
5. Model training  
6. Performance evaluation  

---


---

## Requirements

Typical dependencies used in this project:

- Python 3.x  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  


---

## Results

- MobileNetV2 provides faster training and lower resource usage  
- ResNet50V2 achieves higher accuracy due to deeper architecture  
- Trade-off observed between efficiency and performance  

---

## Use Cases

- Image classification tasks  
- Model comparison studies  
- Learning transfer learning and fine-tuning  
- Understanding CNN architecture differences  

---

## Future Improvements

- Use larger and more diverse datasets  
- Hyperparameter tuning  
- Add more models for comparison (EfficientNet, VGG)  
- Deploy model as a web or mobile application  

---

## Notes

- Pretrained weights are used for transfer learning  
- Performance may vary depending on dataset size and quality  
- GPU is recommended for faster training  

---
