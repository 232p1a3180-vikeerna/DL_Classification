Project Title:

__Traffic Sign Recognition Using Deep Learning__

Project Overview:

This project is a Traffic Sign Recognition System built using Deep Learning and TensorFlow/Keras. The model classifies traffic sign images into 43 different categories and predicts the corresponding traffic sign label.

Features:

* Image classification using a Convolutional Neural Network (CNN)
* Supports 43 traffic sign classes
* Automatic image preprocessing
* Real-time prediction from uploaded images
* Displays the predicted traffic sign with the image

 Dataset:

The model is trained on the German Traffic Sign Recognition Benchmark (GTSRB) dataset, which contains thousands of labeled traffic sign images across 43 categories.

Technologies Used:

* Python
* TensorFlow/Keras
* NumPy
* Pillow (PIL)
* Matplotlib

Project Structure:

traffic-sign-recognition/

├── traffic_sign_classifier.h5

├── dataset/

├── report file

├── images/

└── README.md

 How It Works:

1. The user uploads an image to the `input` folder.
2. The image is resized to 30×30 pixels.
3. The trained CNN model processes the image.
4. The model predicts the traffic sign class.
5. The result is displayed along with the uploaded image.

Installation:

Install the required libraries:

pip install tensorflow numpy pillow matplotlib

 Usage:

Run the prediction script:

python predict.py

Place a traffic sign image inside the `input` folder. The model will automatically detect and classify the sign.

 Model Performance:

The CNN model was trained and evaluated on the GTSRB dataset and achieved high accuracy in traffic sign classification.

Applications:

* Smart Transportation Systems
* Autonomous Vehicles
* Driver Assistance Systems
* Road Safety Monitoring

Future Improvements:

* Real-time webcam detection
* Mobile application integration
* Support for additional traffic signs
* Improved model accuracy using transfer learning

