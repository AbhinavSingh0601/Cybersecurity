# ML-Based Cybersecurity Project

## Overview
This project leverages Machine Learning (SVC - Support Vector Classifier) to provide real-time cybersecurity threat detection. The model is trained on two datasets and is integrated into a web application for live predictions.

## Features
- Machine Learning model (SVC) for cybersecurity threat detection.
- Web interface for real-time predictions.
- Backend in Python (Flask) and Node.js for handling requests.
- Frontend in HTML, CSS, and JavaScript.

## Installation
To run this project, ensure you have Python and Node.js installed.

### 1. Install Dependencies
#### Python Dependencies
```sh
pip install -r requirements.txt
```

#### Node.js Dependencies
```sh
cd server
npm install
```

## Running the Application
### 1. Start the Python Backend
```sh
python app.py
```

### 2. Start the Node.js Server
```sh
node server.js
```

### 3. Open the Web Interface
- Open `index.html` in a browser.
- Enter the required inputs for real-time predictions.


## Model Details
- **Algorithm:** Support Vector Classifier (SVC)
- **Datasets:** Two datasets related to cybersecurity threats
- **Preprocessing:** Feature scaling, data normalization
- **Training:** Scikit-learn used for model training and evaluation

## API Endpoints
### 1. Python API (Flask)
- **`POST /predict`** - Accepts input data and returns predictions

### 2. Node.js Server
- **Handles additional processing and web requests**

## Future Improvements
- Extend to deep learning models (LSTMs, CNNs) for advanced threat detection.
- Improve dataset quality and introduce real-time logging.
- Deploy the project using cloud services for scalability.
