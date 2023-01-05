# Loan Prediction App
This project uses machine learning, Python, and Streamlit to create a web application that predicts the likelihood of a loan being repaid.

## Requirements
Python 3.6 or higher
Streamlit
Other required Python packages (e.g. scikit-learn, pandas)
## Installation
Clone or download the repository
Install the required packages:

```python
   pip install -r requirements.txt
   ```

## Usage
To run the app, navigate to the directory where the app.py file is located and run:

```python
streamlit run app.py
```

The app will then be accessible at http://localhost:8501.

## Data
The data used in this project is available in the data directory. It consists of information on past loans and whether or not they were repaid.

## Model Training
The machine learning model is trained using the train.py script. The training data is loaded from the data directory and the trained model is saved to the models directory.
