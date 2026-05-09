# Health Insurance Premium Prediction App

## Project Overview

This project is a web application built using Streamlit that predicts a user's health insurance premium based on personal, financial, and health-related information.

The application collects user inputs such as age, income, BMI category, smoking habits, employment status, and risk scores, then uses a machine learning prediction model to estimate the insurance premium.

---

# Features

* Interactive web interface
* User-friendly input forms
* Insurance premium prediction
* Real-time prediction output
* Machine learning model integration

---

# Technologies Used

* Python
* Streamlit
* Machine Learning
* Pandas
* NumPy
* Scikit-learn

---

# Project Structure

```text
project-folder/
│
├── main.py
├── prediction_helper.py
├── model.pkl
├── requirements.txt
└── README.md
```

---

# Installation

## 1. Clone the Repository

```bash
git clone <repository-url>
cd <project-folder>
```

---

## 2. Create Virtual Environment (Optional)

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Linux/Mac

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

---

# Run the Application

Use the following command:

```bash
streamlit run main.py
```

After running the command, the application will open in your browser automatically.

---

# Input Parameters

The application accepts the following inputs:

| Parameter            | Description               |
| -------------------- | ------------------------- |
| Age                  | User age                  |
| Region               | Residential region        |
| Number of Dependents | Total dependents          |
| BMI Category         | Body Mass Index category  |
| Income in Lakhs      | Annual income             |
| Insurance Plan       | Selected insurance plan   |
| Genetic Risk         | Genetic health risk score |
| Total Risk Score     | Overall health risk       |
| Gender               | Male/Female               |
| Employment Status    | Job type                  |
| Smoking Status       | Smoking habit             |

---

# Prediction Output

The model predicts:

```text
Estimated Health Insurance Premium
```

Example:

```text
Your estimated Premium is ₹15000
```

---

# How It Works

1. User enters personal and health details.
2. Data is collected using Streamlit input components.
3. Input data is passed to the prediction model.
4. Machine learning model processes the data.
5. Predicted insurance premium is displayed.

---

# Example Command

```bash
streamlit run main.py
```

---

# Future Improvements

* Add database integration
* Improve UI design
* Deploy application online
* Add authentication system
* Improve model accuracy
* Add graphical analytics

---

# Requirements

Example `requirements.txt`

```text
streamlit
pandas
numpy
scikit-learn
joblib
```

---

# Author

Developed by Anugna Batthini
