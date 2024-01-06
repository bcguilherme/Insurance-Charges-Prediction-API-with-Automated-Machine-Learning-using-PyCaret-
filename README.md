# Insurance-Charges-Prediction-API-with-Automated-Machine-Learning-using-PyCaret-

# Insurance Charges Prediction API

This project uses PyCaret to build a regression model predicting insurance charges. The trained model is deployed as an API using FastAPI.

## Setup

```bash
pip install -r requirements.txt

Usage

Run the Jupyter notebook to train and tune the machine learning model:

jupyter notebook insurance_model.ipynb

The final model will be saved in the ../app directory.
Start the API:

uvicorn app.api_insurance:app --reload

The API will be accessible at http://127.0.0.1:8000.

Project Structure

data/: Contains the dataset used for training the model.
app/: Contains the FastAPI application for serving the model.
insurance_model.ipynb: Jupyter notebook for model training and tuning.
requirements.txt: List of Python dependencies.
API Documentation

API documentation: http://127.0.0.1:8000/docs.

Contributing

Contributions are welcome! If you have any ideas, bug reports, or feature requests, please open an issue or submit a pull request.

License

This project is licensed under the MIT License - see the LICENSE file for details.

