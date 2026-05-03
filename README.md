🩺 Chest X-Ray Classification using CNN

This project focuses on building a Convolutional Neural Network (CNN) model to classify chest X-ray images. The goal is to detect medical conditions (such as pneumonia or normal cases) using deep learning techniques.

📌 Project Overview
Built using TensorFlow & Keras
Uses CNN architecture for image classification
Applies data augmentation to improve model performance
Includes training, validation, and model saving
🧠 Model Architecture

The CNN model consists of:

Convolutional Layers (feature extraction)
Batch Normalization (stability & faster training)
Max Pooling (downsampling)
Fully Connected Layers (classification)

Input Shape:

(224, 224, 3)
⚙️ Technologies Used
Python 🐍
TensorFlow / Keras
NumPy
Matplotlib (optional for visualization)
📂 Dataset
Chest X-ray image dataset
Images are divided into:
Training set
Validation set

⚠️ Dataset not included in this repository. Please add your dataset in the appropriate directory.

🔄 Data Preprocessing
Rescaling pixel values (1./255)
Data augmentation:
Rotation
Zoom
Horizontal flip
Shear transformation
🚀 Model Training
Loss Function: binary_crossentropy
Optimizer: Adam
Metrics:
Accuracy
Recall

Callbacks used:

Early Stopping
Reduce Learning Rate on Plateau
💾 Model Saving & Loading

Save model:

model.save("cnn_model.h5")

Load model:

model = tf.keras.models.load_model("cnn_model")
📊 Results
Model trained for multiple epochs
Performance evaluated using:
Accuracy
Recall

(You can add screenshots or graphs here later)

▶️ How to Run
Clone the repository:
git clone https://github.com/your-username/chest-xray-cnn.git
Install dependencies:
pip install tensorflow
Run the notebook:
jupyter notebook
📌 Future Improvements
Use Transfer Learning (e.g., ResNet, VGG16)
Improve dataset size
Add confusion matrix & visualization
Deploy as a web app
👨‍💻 Author
Ritik
(B.Com Graduate | M.Com Pursuing | Data Analytics & Japanese Language Learner)
