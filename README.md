# Tire Anomaly Detection System

## Overview
The **Tire Anomaly Detection System** is a machine learning-based project that utilizes image processing techniques to classify tires as defective or non-defective. The system is designed to assist in automated quality control processes using deep learning models.

## Features
- Image preprocessing for better model training and evaluation.
- A deep learning model (not provided in the repository) that can be trained locally.
- Flask web application for image uploads and predictions.
- Training and testing scripts for model training and evaluation.

## Folder Structure
```
Tire-Anomaly-Detection/
│-- app.py                # Flask web application for predictions
│-- Data_preprocess.py    # Image preprocessing script
│-- test.py               # Model testing script
│-- train.ipynb           # Jupyter Notebook for model training
│-- static/               # Folder for storing images (if applicable)
│-- templates/            # HTML templates for Flask web interface
│-- requirements.txt      # Dependencies for the project
│-- README.md             # Project documentation
```

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Flask
- TensorFlow/Keras
- OpenCV
- NumPy, Pandas, Matplotlib

### Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/Tire-Anomaly-Detection.git
   cd Tire-Anomaly-Detection
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Model Training
Since the trained model is not provided in the repository, you need to train it locally.
1. Open `train.ipynb` in Jupyter Notebook.
2. Follow the steps to preprocess data and train the model.
3. Save the trained model in the appropriate directory for testing and Flask integration.

## Running the Application
1. Start the Flask web application:
   ```sh
   python app.py
   ```
2. Open a browser and navigate to `http://127.0.0.1:5000/`.
3. Upload an image to get predictions.


## Contribution
Contributions are welcome! Feel free to submit issues and pull requests.

## License
This project is licensed under the MIT License.

