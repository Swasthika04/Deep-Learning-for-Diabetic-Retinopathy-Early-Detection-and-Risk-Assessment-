# Deep Learning for Diabetic Retinopathy Early Detection and Risk Assessment

A Flask web app that classifies retinal images into 5 stages of diabetic
retinopathy using a DenseNet121-based CNN model.

## Classes
- 0 - No DR
- 1 - Mild
- 2 - Moderate
- 3 - Severe
- 4 - Proliferative DR

## Tech Used
Python, Flask, TensorFlow/Keras, HTML/CSS/JavaScript

## Project Structure
- app.py - Flask server and prediction route
- utils.py - helper functions for image conversion
- models/model.py - model building and image preprocessing
- templates/ - HTML pages
- static/ - CSS and JavaScript files

## How to Run
1. Install the libraries:
   pip install -r requirements.txt
2. Run the app:
   python app.py
3. Open http://localhost:5000 in your browser and upload a retina image.

## Note
The trained model files (.h5) are not included in this repository
because of their large size.