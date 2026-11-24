# AI-Crop-Disease-Detection
AI Crop Disease Detection is a machine learning and deep learning-based application designed to identify plant diseases by analyzing images of crop leaves.
AI CropAI Crop Disease Detection Using 

AI Crop Disease Detection is a machine learning and deep learning-based application designed to identify plant diseases by analyzing images of crop leaves.

The system uses Convolutional Neural Network (CNN) concepts and MobileNetV2 transfer learning to classify uploaded leaf images into different disease categories or healthy classes.
The main objective is to help farmers and agricultural students understand how Artificial Intelligence can support early crop disease identification.

* Detect possible crop diseases using leaf images.
* Apply deep learning for image classification.
* Build an easy-to-use web application.
* Display predicted disease categories and confidence scores.
* Demonstrate the use of AI in smart agriculture.

⚙️ Technologies Used

* Python
* TensorFlow and Keras
* MobileNetV2
* Deep Learning
* Streamlit
* NumPy
* Pillow

1. Upload crop leaf images.
2. AI-based image classification.
3. Identify possible disease categories.
4. Detect healthy leaf categories.
5. Display prediction confidence.
6. Show top three prediction results.
7. Interactive web interface.
How It Works

1. User uploads a crop leaf image.
2. The image is resized to 224 × 224 pixels.
3. MobileNetV2 extracts important image features.
4. The trained model classifies the image.
5. The application displays the predicted class and confidence score.

📂 Project Structure

AI_Crop_Disease_Detection/
│
├── app.py
├── train.py
├── requirements.txt
├── README.md
│
├── data/
│   └── plantvillage/
│       ├── Tomato___Early_blight/
│       ├── Tomato___healthy/
│       └── Potato___Late_blight/
│
└── models/
    ├── crop_disease_model.keras
    └── class_names.json. 

 Installation and Execution

Step 1: Clone the repository

git clone https://github.com/YOUR-USERNAME/AI-Crop-Disease-Detection.git

Step 2: Open the project folder

cd AI-Crop-Disease-Detection

Step 3: Install required libraries

pip install -r requirements.txt

Step 4: Prepare the dataset

Download a labeled plant-leaf dataset such as PlantVillage and arrange images into separate class folders inside:

data/plantvillage/

Step 5: Train the AI model

python train.py

Step 6: Run the application

streamlit run app.py

Expected Output

The application displays:

* Uploaded crop leaf image.
* Predicted disease or healthy class.
* Model confidence percentage.
* Top three prediction results.

Future Enhancements

* Add more crop varieties and disease categories.
* Add disease explanation and verified treatment guidance.
* Support multiple regional languages.
* Integrate a weather-based crop monitoring system.
* Add Grad-CAM visual explanations.
* Deploy the application online.

Limitations

This is an educational prototype. Prediction accuracy depends on the dataset and image quality. The model may not work reliably on real-world field images. Always verify suspected diseases with an agricultural expert before taking treatment decisions.

Project Category

Artificial Intelligence and Machine Learning

Conclusion

AI Crop Disease Detection demonstrates how deep learning and image processing can be applied to agriculture. By identifying possible plant diseases from leaf images, this project showcases the potential of AI in supporting smarter and more efficient farming.

⸻

Developed using Python, TensorFlow, MobileNetV2 and Streamlit.