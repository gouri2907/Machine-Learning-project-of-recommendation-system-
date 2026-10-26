# PlantCare AI 🌿

## Plant Disease Detection and Treatment Recommendation System Using Machine Learning

### Project Overview
PlantCare AI is a machine learning project that classifies tomato leaf images into 10 classes, including healthy leaves and different disease categories. It also displays predefined plant-care recommendations based on the predicted class.

### Objectives
- Detect possible tomato leaf diseases from images.
- Classify leaf images using deep learning.
- Display relevant plant-care recommendations.

### Technologies Used
- Python
- Google Colab
- TensorFlow and Keras
- MobileNetV2
- NumPy
- PIL (Pillow)
- Matplotlib

### Dataset
PlantVillage Tomato Leaf Dataset  
https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset

### Model
MobileNetV2 with transfer learning.

### Results
- Number of classes: 10
- Training epochs: 5
- Test accuracy: 90.24%
- Test loss: 0.2950

### How It Works
1. Load and preprocess tomato leaf images.
2. Train the classification model using transfer learning.
3. Upload a leaf image for prediction.
4. Display the predicted class and model confidence.
5. Retrieve related care recommendations.

### Limitations
The model is focused on tomato leaf images from the selected dataset. Results on real-world images may vary. Predictions are not a confirmed agricultural diagnosis.

### Author
Student Project — PlantCare AI
