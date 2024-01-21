# Pizza_Steak_ImageClassification_CNN
This project introduces a powerful image classification model to distinguish between pizza and steak images. Leveraging advanced techniques, the model achieves robust performance in handling complex visual features.

Link of Data : https://www.kaggle.com/datasets/kelixirr/pizza-steak-image-classification-dataset/data

Key Techniques Employed

Convolutional Neural Network (CNN)
Implemented a sophisticated CNN architecture utilizing TensorFlow and Keras, designed to learn intricate hierarchical patterns in the images.

Data Augmentation
Applied data augmentation techniques to enrich the training dataset, enhancing the model's ability to generalize to various image variations.

Dropout Layer
Incorporated dropout layers to combat overfitting, ensuring the model's robustness by preventing reliance on specific features.

Model Evaluation
Evaluated model performance in different scenarios:
Model 1: Created a baseline CNN model.
Model 2: Implemented data augmentation and added a dropout layer to observe improvements.

Results
Model 1
Epoch 1:

Training Loss: 0.5318 | Accuracy: 73.00%
Validation Loss: 0.4147 | Accuracy: 82.40%
Epoch 2:

Training Loss: 0.4205 | Accuracy: 82.73%
Validation Loss: 0.3691 | Accuracy: 86.60%
Epoch 3:

Training Loss: 0.3714 | Accuracy: 84.33%
Validation Loss: 0.3446 | Accuracy: 85.40%
Epoch 4:

Training Loss: 0.3533 | Accuracy: 85.07%
Validation Loss: 0.3521 | Accuracy: 82.80%
Epoch 5:

Training Loss: 0.2933 | Accuracy: 88.40%
Validation Loss: 0.3474 | Accuracy: 85.40%
Model 2 (with Data Augmentation and Dropout)
Epoch 1:

Training Loss: 0.6502 | Accuracy: 61.20%
Validation Loss: 0.5418 | Accuracy: 72.20%
Epoch 2:

Training Loss: 0.5278 | Accuracy: 73.73%
Validation Loss: 0.3789 | Accuracy: 82.00%
Epoch 3:

Training Loss: 0.4948 | Accuracy: 75.93%
Validation Loss: 0.3645 | Accuracy: 85.40%
Epoch 4:

Training Loss: 0.4827 | Accuracy: 77.20%
Validation Loss: 0.3348 | Accuracy: 85.80%
Epoch 5:

Training Loss: 0.4697 | Accuracy: 78.80%
Validation Loss: 0.3307 | Accuracy: 87.40%
These results showcase the progression and improvements observed in Model 2 after incorporating data augmentation and dropout layers. Model 2 demonstrates enhanced generalization and reduced overfitting, as reflected in the validation accuracy.








