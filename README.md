🌱 Plant Disease Detection using Deep Learning

A deep learning-based image classification project that detects and classifies plant leaf diseases from images using PyTorch, CNNs, and transfer learning.

This system helps in early plant disease identification, allowing faster treatment decisions and improved crop productivity.

📌 Project Overview

Plant diseases are one of the major causes of reduced agricultural yield.
This project uses computer vision and deep learning to automatically classify diseases from plant leaf images.

The model is trained using the Kaggle New Plant Diseases Dataset by vipoooool, which contains around 87K RGB images of healthy and diseased crop leaves across 38 classes.

📂 Dataset Used

Dataset: New Plant Diseases Dataset
Source: Kaggle
Link: https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset

📊 Dataset Details
📸 ~87,000 RGB images
🌿 38 disease classes
📁 Pre-split into train and validation sets (80/20)
🧪 33 additional test images for predictions
🍅 Multiple crops included:
Tomato
Potato
Corn
Apple
Grape
Pepper
🛠️ Tech Stack
Python
PyTorch
Torchvision
NumPy
Pandas
Matplotlib
PIL
Google Colab
KaggleHub
⚙️ Project Workflow
Import dataset from KaggleHub
Preprocess image dataset
Apply image transformations
Create DataLoaders
Train CNN / transfer learning model
Validate on validation set
Plot loss and accuracy curves
Predict disease class on test images
🧠 Model Architecture

This project uses CNN-based deep learning architecture for image classification.

Possible models:

Custom CNN
ResNet
EfficientNet
MobileNet
VGG

Replace this with your exact architecture after final training.

📈 Results

The model performs highly accurate classification on multiple crop diseases.

✅ Evaluation Metrics
Training Accuracy
Validation Accuracy
Loss Curve
Prediction Confidence
Class-wise Performance

Example: Validation Accuracy: 98%+

🚀 How to Run
Clone Repository
git clone https://github.com/Samyak523/plant_disease_detection.git
cd plant_disease_detection
Install Dependencies
pip install torch torchvision numpy pandas matplotlib pillow kagglehub
Run Notebook

Open:

crop_disease_detection.ipynb

Run all cells in Google Colab / Jupyter Notebook.

📷 Sample Prediction
Tomato - Early Blight
Confidence: 97.8%
🎯 Future Improvements
🌐 Streamlit web app deployment
📱 Android application integration
☁️ Cloud deployment
🎥 Real-time leaf scanning
💊 Disease treatment recommendation
📍 Fertilizer suggestion system
💼 Resume Relevance

This project showcases:

Deep Learning
Computer Vision
CNN
Transfer Learning
PyTorch
Data Preprocessing
Model Evaluation
Real-world AI in Agriculture

Perfect for:

AI/ML Engineer
Computer Vision Intern
Deep Learning Roles
Data Science Projects
👨‍💻 Author

Samyak Jain
B.Tech CSE | AI/ML Enthusiast
GitHub: https://github.com/Samyak523

⭐ Support

If you found this useful, give it a star ⭐ on GitHub.
