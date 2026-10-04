# Plant-Disease-Detection

🌿 Plant Disease Detection using Deep Learning

📌 Project Overview

This project is a Deep Learning-based Plant Disease Detection system that identifies plant diseases from leaf images.

The model is trained on the PlantVillage dataset and uses image classification techniques to predict the disease category of a given plant leaf image.

🎯 Objective

The main objective of this project is to develop an image classification model that can automatically detect plant diseases from leaf images and help in early identification of plant health problems.

🧠 Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Pillow (PIL)
- Google Colab
- Kaggle Dataset

📊 Dataset

The project uses the PlantVillage dataset, which contains images of healthy and diseased plant leaves across multiple classes.

The dataset is downloaded through Kaggle and is used for training and validation of the deep learning model.

⚙️ Model

The project uses a Convolutional Neural Network (CNN) based image classification approach.

The images are resized to 224 × 224 pixels and normalized before being provided to the model.

🔄 Project Workflow

1. Download the PlantVillage dataset.
2. Load and preprocess the leaf images.
3. Resize images to 224 × 224 pixels.
4. Normalize pixel values.
5. Split the data into training and validation sets.
6. Train the deep learning model.
7. Evaluate the model.
8. Upload a new leaf image.
9. Predict the plant disease class.

🔮 Prediction

After training, the model can take a new plant leaf image as input and predict its corresponding disease class.

Input: Plant leaf image
Output: Predicted disease class

📁 Project Structure

Plant-Disease-Detection/

-->Plant Disease Detection.ipynb
-->README.md
-->(Dataset is not included)

🚀 How to Run

1. Open the notebook in Google Colab.
2. Install the required Python libraries.
3. Set up your own Kaggle API credentials if the dataset needs to be downloaded.
4. Download/load the PlantVillage dataset.
5. Run the notebook cells in order.
6. Train the model.
7. Use the prediction section to test a leaf image.

«Note: "kaggle.json" is not included in this repository for security reasons. Users should use their own Kaggle API credentials.»

📈 Results

The trained model is able to classify plant leaf images into their respective disease categories.

The notebook contains the training, validation and prediction results.

🎓 Educational Purpose

This project has been created for educational and learning purposes to understand the practical implementation of Deep Learning, CNN-based image classification, data preprocessing, model training, and plant disease detection.

The project is intended for academic and demonstration purposes and should not be considered a professional agricultural or medical diagnostic system.

🔐 Security Note

Private API credentials such as "kaggle.json" should never be uploaded to GitHub.

👨‍💻 Author

Deepak Garkoti 

Student | B.Tech CSE (AI & ML)

---

⭐ If you find this project useful, feel free to explore the notebook and learn from it.