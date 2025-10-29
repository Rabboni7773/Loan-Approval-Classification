 # 📄 Loan Prediction Model - Random Forest 


This project implements a Loan Prediction Model using the Random Forest classification algorithm to determine the likelihood of a loan applicant being approved or rejected based on various features.

## 🎯 Project Goal
The primary goal of this project is to build a machine learning model that can accurately predict loan approval status. This can help financial institutions automate and streamline their decision-making process, reducing risk and improving efficiency.

## 🛠️ Technology Stack
The following technologies and libraries were used in this project:

--Python: The core programming language.

--Jupyter Notebook / Google Colab: For exploratory data analysis and model development.

--Pandas & NumPy: For data manipulation and numerical operations.

--Scikit-learn: For implementing the Random Forest Classifier, model training, and evaluation.

--Matplotlib & Seaborn: For data visualization.

## 💻 How to Run Locally
Follow these steps to set up and run the project on your local machine:

### 1. Clone the Repository
-- git clone https://github.com/Rabboni7773/Loan-Approval-Classification.git
-- cd Loan-Approval-Classification

### 2. Create a Virtual Environment (Optional but Recommended)
-- python -m venv venv
-- source venv/bin/activate  # On Linux/macOS
-- .\venv\Scripts\activate   # On Windows

### 3. Install Dependencies
-- pip install -r requirements.txt


### 4. Run the Notebook
--Open and run the main notebook file (loan_prediction_rf.ipynb or similar) in your chosen environment (e.g., Jupyter, VS Code).




## 📊 Model Performance
The Random Forest Classifier achieved the following performance metrics:

###   Metric                   Value
    Accuracy        0.9160063076775404
    Precision       0.8863408291163115
    Recall          0.7091216216216216
    F1-Score        0.7865689795870311
    ROC-AUC         0.9648054853766957

## 🔗 Files in the Repository


--loan_prediction_model.ipynb: The main notebook containing data cleaning, EDA, model training, and evaluation.

--loan_data.csv: The dataset used for training the model.

--requirements.txt: List of all required Python packages.