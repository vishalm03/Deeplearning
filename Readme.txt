Team 19: Weather Image Classification Using Deep Learning


Objectives
Develop a deep learning model to classify images into predefined weather categories (e.g., sunny, cloudy, rainy, snowy, etc.).
Explore the effectiveness of transfer learning using pretrained models such as ResNet or VGG.
Achieve high classification accuracy across different weather conditions, while maintaining generalization.
Deploy the model in a user-friendly interface, allowing users to upload images and get weather predictions in real-time.

Key Components: 

Model Development
Build a Convolutional Neural Network (CNN) from scratch to classify weather conditions.
Fine-tune a pretrained CNN model (e.g., ResNet or VGG) using transfer learning to enhance performance with a small dataset.
Experiment with different hyperparameters and architectures to optimize the model.

Model Evaluation
Split the dataset into training, validation, and test sets.
Evaluate the model using accuracy, F1-score, and confusion matrix to ensure balanced classification across all categories.
Use visualizations like Grad-CAM to interpret model predictions and understand feature importance.

Deployment and Interface Design
Develop a web-based interface using Gradio or a similar tool to allow users to upload weather images and receive real-time predictions.
Host the model on a cloud service (e.g., AWS, Google Cloud) for easy access.

Expected Outcomes
A deep learning model capable of classifying weather conditions from images with high accuracy.
A user-friendly web interface for real-time weather image classification.
Insights into the challenges of weather image classification and the effectiveness of CNNs and transfer learning for this task.