# Heart Disease Prediction

This Python script is designed to predict whether an individual is likely to have heart disease or not based on certain health-related features. It utilizes a pre-trained machine learning model to make predictions.

## Dataset

- **Dataset Name**: Heart Disease dataset
- **Data Source**: dataset upload on git
- The dataset contains the following attributes:
  - Feature columns (13): Various health-related features such as age, sex, chest pain type, etc.
  - Target column: Binary variable (0 for no heart disease, 1 for heart disease).

## Project Structure

- **README.md**: Documentation of the project.
- **main.py**: Python script for making heart disease predictions.
- **model.joblib**: Pre-trained machine learning model for heart disease prediction.

## Setup

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd heart-disease-prediction
2. Create a virtual environment (recommended) and install the required dependencies:
   ```bash
   python -m venv venv
   source venv/bin/activate # On Windows, use: venv\Scripts\activate

## Usage
`Clone this repository to your local machine.
`Ensure you have the pre-trained machine learning model ('model.joblib') in the same directory as the script ('main.py').
`Open a command prompt or terminal and navigate to the directory where the script is located.
`Run the script with the appropriate input values.

 ## For example:
    ```python main.py --age 63, --sex 1, --cp 3, --trestbps 130, --chol 230, --fbs 1, --restecg 0, --thalach 150, --exang 0, --oldpeak 2.3, --slop 2, --ca 0 --thal 2

## Model Training
The project uses a machine learning model to classify individuals into two classes: heart disease and no heart disease. The pre-trained model is saved as 'model.joblib'.

##  Evaluation
The script provides binary predictions. You can evaluate the model's performance using metrics like accuracy, precision, recall, and F1-score.

## Results
The project provides predictions for heart disease based on the input features. The performance of the model may vary depending on the dataset used.

## Future Improvements
There are several ways to improve the model and the project:

`Explore more advanced machine learning techniques.
`Fine-tune hyperparameters for better model performance.
`Gather more labeled data for improved accuracy.

## References

- Author: Mirza Salman
- Contact: salmansaluu661@gmail.com

Feel free to customize this README to include any additional information you want to provide about the project.
