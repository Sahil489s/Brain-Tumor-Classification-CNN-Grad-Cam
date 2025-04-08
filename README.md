# Brain-Tumor-Classification-CNN-Grad-Cam

This project uses Convolutional Neural Networks (CNN) to classify brain MRI images into four categories: **Glioma**, **Meningioma**, **Pituitary Tumor**, and **No Tumor**. It also includes **Grad-CAM visualizations** to interpret the model's focus on tumor regions.

## 📂 Dataset
- Brain MRI images from publicly available Kaggle datasets.
- Images are preprocessed and resized before feeding into the model.

## 🧠 Model
- CNN built using **TensorFlow** and **Keras**.
- Includes **data augmentation** and **dropout** to prevent overfitting.
- Achieved **~99% validation accuracy**.

## 📊 Results
- **Confusion Matrix**: High classification performance across all categories.
- **Grad-CAM**: Highlights regions where the model focuses while predicting.
- **Accuracy/Loss Curves**: Smooth convergence and no overfitting.

## 📸 Sample Visuals
- Training Accuracy vs Loss Graph
- Confusion Matrix
- Grad-CAM Heatmaps on MRI

## 🛠️ Tech Stack
- Python, TensorFlow, Keras, Matplotlib, NumPy

## 🔍 Future Improvements
- Test on unseen datasets
- Try transfer learning (e.g., ResNet, VGG)
- Deploy as a web app with Streamlit or FastAPI
