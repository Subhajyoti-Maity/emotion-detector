# 🎭 Emotion Detector

This is a **Flask-based web application** that detects human emotions from audio files using a deep learning model.

## 📌 Features
- Upload an audio file and get the predicted emotion.
- Pre-trained deep learning model (`emotion_model.h5`).
- Simple and clean web interface built with HTML and Flask.
- Supports `.wav` audio format.

## 🛠️ Tech Stack
- **Backend:** Python, Flask
- **Frontend:** HTML, CSS
- **Machine Learning:** Keras/TensorFlow
- **Audio Processing:** Librosa

## 📂 Project Structure
app.py # Main Flask application
emotion_model.h5 # Pre-trained emotion detection model
templates/
└── index.html # Frontend UI
static/ # Audio samples & static files

bash
Copy
Edit

## 🚀 How to Run
1. **Clone the repository**
```bash
git clone https://github.com/Subhajyoti-Maity/emotion-detector.git
cd emotion-detector
2. Create and activate a virtual environment

bash
Copy
Edit
python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate

3. Install dependencies

bash
Copy
Edit
pip install -r requirements.txt

 4. Run the app

bash
Copy
Edit
python app.py

5. Open in browser

cpp
Copy
Edit
http://127.0.0.1:5000

📊 Model Details
Trained on audio datasets for emotion recognition.

Extracts MFCC features from .wav files.

Predicts emotions such as happy, sad, angry, neutral, fear, disgust, surprise.
