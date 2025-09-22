# DS_SolarPanel_Defect_Detection_using_DeepLearning

🌞 Solar Panel Defect Detection using Deep Learning and Streamlit
A complete end-to-end deep learning pipeline to detect and classify defects in solar panels using PyTorch CNN models. This project includes data cleaning, augmentation, training multiple models (Basic CNN, ResNet18, EfficientNet-B0, and MobileNetV2), and deploying the best model through a Streamlit web app.

## 📌 Project Highlights

✅ Image Cleaning: Removed non-image files, corrupted, duplicate, and unwanted files.

🏷️ Label Encoding: All 6 classes encoded for supervised classification.

⚖️ Data Augmentation: Applied transforms to balance dataset and reduce overfitting.

🧹 Class Imbalance Handling: Addressed using weighted sampling.


## 🧠 Model Architectures:

Basic CNN

ResNet18

EfficientNet-B0 ✅ (Best performance)

MobileNetV2


## 🧪 Model Evaluation:
Accuracy, loss tracking on train/validation/test sets.

## 📦 Model Saving:
All models are saved locally for reuse.

## 🌐 Deployment:
Streamlit app deployed using pyngrok to serve predictions.


## 🧪 Classes
The model classifies images into the following 6 categories:

#### Bird-drop

#### Clean

#### Dusty

#### Electrical-damage

#### Physical-damage

#### Snow-covered


## ⚙️ Technologies Used
Python

PyTorch

torchvision

NumPy, Pandas

Matplotlib (for visualization)

Streamlit

pyngrok (for deployment)

Google Colab (for GPU-based training)


## 🚀 Streamlit Deployment
To run the Streamlit app:

pip install streamlit pyngrok torch torchvision
streamlit run app.py
You will receive a public URL (via pyngrok) to access the app online.

## 📊 Model Performance Summary


# Model	Accuracy	  Notes
Basic CNN	~78%	    Initial baseline
ResNet18	~85%	    Good accuracy, faster train
MobileNetV2	~88%	  Lightweight and efficient
EfficientNet-B0   	✅ 91%	Best accuracy + low overfit

## Final model: EfficientNet-B0 chosen for deployment due to superior performance.

## 📌 Features of the Streamlit App

Upload solar panel image

Model predicts the defect class

Displays label and confidence

Clean and intuitive UI

## 📄 Project Report
Solar_Panel_Defect_Detection_Report.docx


