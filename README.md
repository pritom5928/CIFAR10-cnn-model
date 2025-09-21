# CIFAR-10 Image Classification with CNN

This project uses a **Convolutional Neural Network (CNN)** built with TensorFlow/Keras to classify colored images (32×32×3) from the CIFAR-10 dataset.  
It achieves **~84% accuracy** on the test set.

---

## 📌 Project Structure
- `CIFAR10_Image_Classification(CNN).ipynb` → Google Colab/Jupyter notebook with full code.  
- `cifar10_cnn_model.keras` → Saved trained model (can be loaded without retraining).  
- `requirements.txt` → Required Python libraries with versions.  
- `sample_predictions/` → Example predictions on test images with labels.  

---

## 🚀 Dataset Info
- **Dataset:** CIFAR-10 (60,000 images, 32×32, RGB)  
- **Classes (10):** airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck  

---

## 📊 Results
- **Training Accuracy:** ~86%  
- **Validation Accuracy:** ~84%  
- **Test Accuracy:** ~84%  

---

## 📷 Sample Predictions

| Image | Prediction |
|-------|------------|
| ![](sample_predictions/airplane.png) | airplane |
| ![](sample_predictions/cat.png)      | cat |
| ![](sample_predictions/ship.png)     | ship |

---
