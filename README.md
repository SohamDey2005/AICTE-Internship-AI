# AICTE Internship on AI: Transformative Learning with TechSaksham – A joint CSR initiative of Microsoft & SAP

🌿 Potato Leaf Disease Detection 

🏆 Overview
This project is a Potato Leaf Disease Detection Web App built using Streamlit. The app allows users to upload an image of a potato leaf and predicts whether the leaf shows signs of:
🥀 Early Blight
🌧️ Late Blight
🍃 Healthy

✨ Features
🎨 User-Friendly Interface: Intuitive design for seamless image upload and prediction.

🔍 Accurate Disease Prediction: Classifies potato leaves into:
Potato__Early_blight
Potato_Late_blight
Potato__healthy

📊 Confidence Score: Displays prediction confidence level.

🛑 Diseases Explained
🥀 Early Blight
Cause: Caused by the fungus Alternaria solani.
Symptoms: Characterized by small, irregular brown spots with concentric rings on the leaves. Often begins with older leaves.
Impact: Can reduce photosynthesis, leading to decreased yield.

🌧️ Late Blight
Cause: Caused by the oomycete Phytophthora infestans.
Symptoms: Presents as large, irregular gray-green or brown water-soaked lesions. Can spread rapidly in wet conditions.
Impact: Extremely destructive, often resulting in complete crop loss if untreated.

🍃 Healthy
Description: Leaves are free from visible spots, lesions, or discoloration. Indicate optimal plant health.

💻 Technologies Used
Frontend: Streamlit for interactive UI.
Backend: TensorFlow and Keras for deep learning.
Language: Python.
Model: Custom CNN trained on potato leaf images.

🚀 How Web Application Works

📂 Image Upload: Upload a potato leaf image in jpg, jpeg, or png format.

🧠 AI Prediction: The app preprocesses the image and uses a deep learning model to predict the disease.

📈 Result Display: View the predicted class and confidence score.

🛠️ Installation
📋 Prerequisites

Python 3.7 or higher

Required libraries:
streamlit
tensorflow
numpy

📂 File Structure
app.py: Main Streamlit app script.
model.h5: Pre-trained TensorFlow model.

📊 Dataset
The model was trained on a curated dataset of potato leaf images, covering:
Early Blight
Late Blight
Healthy leaves

🎯 Usage
Launch the app.
Upload a clear potato leaf image.
Click Predict.
View the prediction and confidence score.
