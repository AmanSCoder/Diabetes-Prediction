# Diabetes Prediction Website

Welcome to the Diabetes Prediction Website! This web application leverages advanced data science techniques to predict the likelihood of diabetes based on various health parameters. The backend is powered by Flask, and the frontend is built using HTML.

## LinkedIn Post
[Linked Post Link](https://www.linkedin.com/feed/update/urn:li:activity:7160519070541389824?utm_source=share&utm_medium=member_desktop)

## Project Overview

### Exploratory Data Analysis (EDA)

EDA is a crucial data exploration technique used to understand various aspects of the data. It serves as the preliminary step in the data analysis process, employing visual and quantitative methods to uncover trends, patterns, and relationships. EDA helps in identifying underlying structures, extracting important variables, detecting anomalies, and testing assumptions.

### Feature Selection

Feature Selection is an essential process to identify the most significant variables that contribute to the prediction outcome. By selecting the critical variables, the model complexity is decreased, performance is improved, and computational cost is reduced.

### Hyperparameter Tuning

Hyperparameter tuning involves finding the optimal combination of hyperparameters to maximize the model's performance. By optimizing these parameters, the learning process is tailored to achieve better predictive results.

### GridSearchCV

GridSearchCV is a technique used to iterate through predefined hyperparameters and fit the model on the training set. It systematically performs this process based on cross-validation, ensuring that each combination of parameters is trained and evaluated on each fold.

## Tech Stack

- **Frontend**: HTML, CSS
- **Backend**: Flask
- **Machine Learning**: Scikit-learn

## Attributes in Dataset

- **Pregnancy**
- **Glucose**
- **BloodPressure**
- **SkinThickness**
- **Insulin**
- **BMI**
- **DiabetesPedigreeFunction**
- **Outcome**

## Installation

To run the Diabetes Prediction Website locally, follow these steps:

### Prerequisites

- Python 3.x
- Flask
- Scikit-learn

### Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/diabetes-prediction.git
    cd diabetes-prediction
    ```

2. Create a virtual environment:

    ```bash
    python3 -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`
    ```

3. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Run the Flask server:

    ```bash
    flask run
    ```

The application should now be running on `http://localhost:5000`.

## Usage

1. Open your web browser and navigate to `http://localhost:5000`.
2. Enter the required health parameters in the input form.
3. Click the "Predict" button to see the prediction result.

## File Structure
```
diabetes-prediction/
├── Dataset
│ └── diabetes.csv
├── Notebook
│ └── Decision_Tree_SVC.ipynb
│ └── Logistic_Regression.ipynb
|
├── templates/
│ └── index.html
|
├── application.py
├── model
| └── modelForPrediction.pkl
│ └── standardScalar.pkl
|
├── requirements.txt
└── README.md
```

- **`application.py`**: The main Flask application file.
- **`modelForPrediction.pkl`**: The pre-trained machine learning model for diabetes prediction.
- **`templates/index.html`**: The HTML template for the web page.


## Contributing

We welcome contributions! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature-name`).
6. Create a new Pull Request.


## Contact

For any inquiries or feedback, please contact us at amansrivastava7969@gmail.com.

---

Thank you for using the Diabetes Prediction Website! We hope this tool helps you in assessing the likelihood of diabetes and taking necessary health precautions.
