# Multimodal HyDeepNet Based Paddy Crop Leaf Disease Prediction System 

This project provides a precise and efficient method for detecting and classifying paddy crop leaf diseases using advanced deep learning and feature fusion techniques.  

The system preprocesses images using techniques like rescaling, flipping, rotation, and zooming to enhance data quality and model robustness. Two deep learning models are used:  
1. **AlexNet-Inspired Architecture** for 227x227 inputs with convolutional layers and dropout for better generalization.  
2. **MobileNetV2 Pretrained Model**, fine-tuned for 256x256 inputs, with added layers for accurate classification.  

Features from both models are extracted and fused for improved representation. These multimodal features are classified using machine learning models like SVM, KNN, and KSVM with RBF kernels, achieving high classification accuracy.  
