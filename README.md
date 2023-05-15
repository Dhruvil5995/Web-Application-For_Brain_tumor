# Web-Application-For_Brain_tumor

This project is a Flask-based web application for detecting brain tumors using a pre-trained deep learning model.

## Getting Started

### Prerequisites

- Python 3.6 or higher
- Flask
- Keras
- NumPy
- PIL (Python Imaging Library)
- OpenCV

### Installation

1. Clone the repository:
2. Change into the project directory:
3. Install the required Python packages:


### Usage

1. Start the Flask application:

2. Open your web browser and go to `http://localhost:5000`.

3. Upload an MRI brain scan image in JPEG, JPG, or PNG format.

4. Click the "Predict" button to perform brain tumor detection.

5. The prediction result will be displayed on the page along with the uploaded image.

## Directory Structure

- `app.py`: The Flask application script that handles routing and prediction logic.
- `index.html`: The HTML template for the web interface.
- `static/`: Directory containing static files such as CSS stylesheets and uploaded images.
- `templates/`: Directory containing HTML templates used by Flask.

## Model

The brain tumor detection model (`brain_tumor.h5`) used by this application is pre-trained using deep learning techniques. It is loaded and used for prediction in the Flask application.








