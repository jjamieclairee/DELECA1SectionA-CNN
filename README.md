ST1504 DEEP LEARNING CA1 SECTION A 

Preface
- This project was undertaken as part of the Deep Learning Essentials module (ST1504), with the objective of applying convolutional neural networks (CNNs) to a real-world image classification task. The assignment required not only building and training a deep learning model, but also evaluating, tuning, and improving it for optimal performance.
Throughout this exercise, I gained hands-on experience with the full machine learning workflow — from data preparation and augmentation, to model building, evaluation, and hyperparameter tuning. The structured approach helped reinforce key concepts in convolutional layers, overfitting mitigation, and the importance of reproducible, well-documented experimentation.

Background Information
1. Project Objective
- The aim of this project is to develop a CNN model that can classify grayscale vegetable images into one of 11 classes. These images vary in resolution and were organized into train, validation, and test folders, with some degree of class imbalance.
2. Dataset Overview
- Input Type: Grayscale images
- Image Sizes Used: 23×23 and 101×101
- Number of Classes: 11
- Class Imbalance: Present — addressed using class weighting and careful EDA
3. Techniques Used
- Image Preprocessing: Normalization, resizing, rescaling
- Class Imbalance Mitigation: class_weight from sklearn.utils.class_weight
- Model Architecture: 3 convolutional layers with max pooling and dropout
4. Training Enhancements:
- EarlyStopping to prevent overfitting
- ReduceLROnPlateau for adaptive learning rate adjustment
5. Hyperparameter Tuning:
- Manually and programmatically tuned:
  - dropout_rate
  - dense_units
  - learning_rate
  - batch_size
- Best-performing models were tracked and saved
6. Performance Visualization:
- Training/validation accuracy and loss curves
- Confusion matrices and classification reports
- Test accuracy comparison across input sizes and configurations
