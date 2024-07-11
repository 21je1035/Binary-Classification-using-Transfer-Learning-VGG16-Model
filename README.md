# Binary-Classification-using-VGG16
***Dogs vs Cats Binary Classification***
This project focuses on a binary classification task to differentiate between images of dogs and cats. The dataset used for this project is the popular Dogs vs Cats dataset provided on Kaggle.

***Project Overview***
The goal of this project is to build a model that can accurately classify images as either a dog or a cat. To achieve this, we utilize a pre-trained VGG16 model from tensorflow.keras and fine-tune it to suit our specific classification task.

***Model and Training***
+ Pre-trained Model  
We used the VGG16 model, a well-known deep learning model for image classification tasks, as the base model for transfer learning. By fine-tuning this model, we leverage its learned features for our classification task.

+ Training Process  
Epochs: 10 (can be increased for potentially better performance)  
Batch Size: Configurable
Accuracy: Achieved approximately 96.5% accuracy on the validation set after 10 epochs.  
+ Dataset  
Training Data: Used only the training part of the dataset.  
Validation Data: Created from the training data for model validation.  
Testing Data: Created from the training data (can also use the test data provided by kaggle itself)  
+ Results
Achieved approximately 96.5% accuracy after 10 epochs.  
The model's performance can be further improved by adjusting the number of epochs and the batch size.
