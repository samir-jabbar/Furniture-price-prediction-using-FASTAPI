# Furniture Price Prediction using FASTAPI

This is a simple project for predicting furniture prices using a machine learning model and serving it through a FASTAPI web application. The project is developed by Samir Jabbar.

## Getting Started

To get started with this project, follow these steps:

Clone the repository:

git clone https://github.com/samir-jabbar/Furniture-price-prediction-using-FASTAPI.git

Install the necessary dependencies. You can use pip to install the required packages:

Start the FASTAPI server:

uvicorn app:app --reload

Visit the FASTAPI Swagger Documentation at http://{port}:8000/docs to interact with the API and make predictions.

## Folder Structure

The project directory structure is as follows:

templates/: Contains the HTML template for the web interface.

1.png, 2.png: Images of running using fastapi docs interface.

Furniture prediction notebook.ipynb: Jupyter Notebook containing data analysis and model training.

README.md: This file.

app.py: The main FASTAPI application with API endpoints for prediction.

furniture.csv: Dataset containing furniture data used for model training.

model.pkl: Pre-trained machine learning model for price prediction.

## Usage

Start the FASTAPI server as mentioned in the "Getting Started" section. Use the Swagger Documentation at http://localhost:8000/docs to test the API and make price predictions.

 ## Dependencies

The project relies on the following Python libraries and frameworks:

FASTAPI

scikit-learn

Pandas

Numpy

## Contributing

Samir JABBAR
