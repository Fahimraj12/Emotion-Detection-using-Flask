# Emotion-Detection-using-Flask
Emotion Detection using Flask is the project of Final Submission of IBM Developing AI Apps using python and flask

## 📌 Project Overview
A web-based emotion detection system that analyzes text input to identify emotional states, developed as the final project for IBM's "Developing AI Apps using Python and Flask" course. This application uses Natural Language Processing (NLP) and machine learning to classify text into various emotional categories.

## ✨ Features
- Real-time Emotion Analysis: Instantly detects emotions from input text
- Multi-Emotion Classification: Identifies happiness, sadness, anger, fear, love, surprise, and more
- Web Interface: User-friendly Flask web application
- REST API Endpoint: Programmatic access to emotion detection functionality
- Confidence Scores: Displays probability scores for each detected emotion
- Response History: Optional logging of previous analyses

## 🔧 Installation & Setup
#### Prerequisites
- Python 3.7+
- pip (Python package manager)
- Git

### Step-by-Step Installation
1. Clone the Repository
```
git clone https://github.com/yourusername/Emotion-Detection-using-Flask.git
cd Emotion-Detection-using-Flask
```
2. Create Virtual Environment
```
python -m venv venv
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate
```
3. Install Dependencies
```
pip install -r requirements.txt
```

### 🚀 Usage
###### Running the Application Locally
- Start the Flask Server
```
python app.py
```
###### Access the Application
- Open your browser and navigate to:
```
http://localhost:5000
```

### Using the Web Interface
1. Enter text in the input box
2. Click "Detect Emotion"
3. View results with emotion classification and confidence scores
