This is a ML couse project titled Optimzing DNN's for edge device deployment using Unstructured Pruning.
This project mainly focuses on improving model's accuracy and reducing the model size while maintaining optimum efficiency


Methodology  
Dataset Preparation: Images resized to 224x224 pixels, normalized, and augmented for consistency and robustness.
Model Selection: MobileNetV3-Small, a lightweight neural network, used with pretrained weights for transfer learning.

Optimization Techniques:
Unstructured Pruning: Eliminates low-magnitude weights to reduce model size and computational complexity.
Training: Cross-entropy loss and Adam optimizer with a learning rate scheduler ensure effective training, tracking accuracy and loss.

Architecture used :
The architecture used for building our model is MobileNet V3 Small.It is a lightweight CNN optimized for mobile and edge devices.


Results
1) The accuracy of the model increased from 90.74% to 93.87%.
2) The size of the model reduced from 5.96MB to 3.64MB.
