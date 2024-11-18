Breast Cancer Classification Using GoogLeNet and AlexNet
Overview
This project aims to classify breast cancer images using deep learning models, specifically GoogLeNet and AlexNet. The models leverage image data to distinguish between different types of breast cancer tissue, aiding in early diagnosis and treatment.

Dataset
The dataset used for this project includes labeled breast cancer images. It comprises:
Training, validation, and testing subsets.
Preprocessed images for optimal model performance.
Note: Specific details about the dataset (source, size, classes) should be included here if available.

Methodology
1. Preprocessing
Resized images to dimensions compatible with GoogLeNet and AlexNet.
Normalized pixel values for consistent input.
2. Model Architecture
GoogLeNet
Inception modules to extract hierarchical features.
Dropout layers to reduce overfitting.
AlexNet
Convolutional layers for spatial feature extraction.
Fully connected layers for classification.
3. Training
Loss Function: Cross-Entropy Loss.
Optimizer: Adam/SGD.
Hyperparameters:
Learning rate: 0.001
batch_size = 32
Epochs: 10
4. Evaluation
Metrics: Accuracy, Precision, Recall, F1-Score.
Confusion Matrix for detailed performance analysis.
Results
GoogLeNet achieved an accuracy of 84.49%.
AlexNet achieved an accuracy of 70.02%.
Include visualizations (e.g., training curves, confusion matrix) for clarity.
