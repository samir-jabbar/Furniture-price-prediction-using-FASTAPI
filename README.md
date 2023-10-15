# Furniture-price-prediction-using-FASTAPI

This is a simple project for predicting furniture prices using a machine learning model and serving it through a FASTAPI web application. The project is developed by Samir Jabbar.

Table of Contents
Project Overview
Getting Started
Folder Structure
Usage
Dependencies
Contributing
License
Project Overview
The project aims to predict furniture prices based on a dataset (furniture.csv) using a pre-trained machine learning model (model.pkl). The predictions are exposed through a RESTful API implemented in app.py using FASTAPI.

Getting Started
To get started with this project, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/samir-jabbar/Furniture-price-prediction-using-FASTAPI.git
Install the necessary dependencies. You can use pip to install the required packages:

bash
Copy code
pip install -r requirements.txt
Start the FASTAPI server:

bash
Copy code
uvicorn app:app --reload
Visit the FASTAPI Swagger Documentation at http://localhost:8000/docs to interact with the API and make predictions.

Folder Structure
The project directory structure is as follows:

templates/: Contains the HTML template for the web interface.
1.png, 2.png: Images used in the project.
Furniture prediction notebook.ipynb: Jupyter Notebook containing data analysis and model training.
README.md: This file.
app.py: The main FASTAPI application with API endpoints for prediction.
furniture.csv: Dataset containing furniture data used for model training.
model.pkl: Pre-trained machine learning model for price prediction.
Usage
Start the FASTAPI server as mentioned in the "Getting Started" section.
Use the Swagger Documentation at http://localhost:8000/docs to test the API and make price predictions.
Dependencies
The project relies on the following Python libraries and frameworks:

FASTAPI
scikit-learn
Pandas
Numpy
You can find the complete list of dependencies in the requirements.txt file.

Contributing
Feel free to contribute to this project by opening issues or creating pull requests. Your contributions are highly appreciated!

License
This project is licensed under the MIT License - see the LICENSE file for details.

Note: Make sure to replace any placeholder information such as author names and URLs with your own if you fork or use this project.
