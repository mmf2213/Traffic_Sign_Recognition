🚦 Traffic Sign Recognition System

This is a Traffic Sign Recognition system built using Convolutional Neural Networks (CNN) and OpenCV. The system allows users to upload an image of a traffic sign and predicts its class using a trained deep-learning model.

📌 Features
✅ Real-time Image Upload: Upload images and get instant predictions
✅ CNN Model: Trained on traffic sign datasets for multi-class classification
✅ Flask-based UI: Clean and responsive interface using Bootstrap 5
✅ OpenCV Processing: Efficient image preprocessing and handling
✅ Fast & Accurate Predictions
📷 Output Screenshots
🔹 Input Image

🔹 Prediction Output

📊 Demo
Input	Prediction

	
🚀 Installation & Setup
🔹 1. Create and Activate Virtual Environment (Optional but Recommended)
python -m venv venv
Activate Virtual Environment:

Windows

venv\Scripts\activate

Mac/Linux

source venv/bin/activate
🔹 2. Install Dependencies
pip install -r requirements.txt
🔹 3. Train the Model (If not already trained)
python model/train_model.py

This will train the CNN model and save it as:

model/traffic_sign_model.h5
🔹 4. Run the Flask Application
python app.py
🔹 5. Open in Browser

Once the server starts, open:

http://127.0.0.1:5000/

Upload an image to get the predicted traffic sign.

⚙️ Technologies Used
🔹 Python 3.8+
🔹 Flask
🔹 TensorFlow / Keras
🔹 OpenCV
🔹 Bootstrap 5
🔹 NumPy, Pandas, Scikit-learn

   👨‍💻 Author
Mrunal Fattepurkar

🤝 Contributing

Contributions are welcome! Feel free to improve the project and submit changes.

⚠️ License

This project is open-source and free to use.