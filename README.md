# Plant Disease Prediction using CNN 🌿

This deep learning project uses a Convolutional Neural Network (CNN) to classify and predict plant diseases from leaf images. The model is trained on the PlantVillage dataset, which contains over 50,000 labeled images of healthy and diseased leaves across multiple plant species.

---

## Dataset

- **Source:** [PlantVillage Dataset on Kaggle](https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset)
- The dataset includes:
  - 38 classes of healthy and diseased plant leaves
  - High-resolution color images
  - Cropped and segmented versions

---

## Model Architecture

- CNN with multiple Conv2D, MaxPooling, and Dropout layers
- ReLU activation functions
- Dense layers for final classification
- Softmax for multi-class output

