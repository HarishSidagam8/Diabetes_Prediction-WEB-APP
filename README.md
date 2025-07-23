# 🩺 Diabetes Prediction App using Streamlit

This is a **machine learning-powered web app** built with **Streamlit** that predicts the likelihood of a person having diabetes based on medical parameters. It uses the **Pima Indians Diabetes Dataset** from the UCI repository and a trained ML model to make predictions in real-time.

---

## 🚀 Features

- 🧮 Predicts diabetes based on:
  - Number of Pregnancies
  - Glucose Level
  - Blood Pressure
  - Skin Thickness
  - Insulin Level
  - BMI (Body Mass Index)
  - Diabetes Pedigree Function
  - Age
- 🎨 Clean and interactive user interface
- 💡 Real-time predictions with a trained model
- 🧠 Built using Python, Streamlit, and scikit-learn

---

## 📊 Tech Stack

| Technology    | Usage                           |
|---------------|----------------------------------|
| Streamlit     | Web interface                    |
| Python        | Core programming language        |
| scikit-learn  | Machine learning model           |
| pandas        | Data processing                  |
| joblib/pickle | Model serialization              |

---

---

## 🛠️ Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/HarishSidagam8/diabetes_prediction_app.git
   cd diabetes_prediction_app

python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate

Create and activate a virtual environment (optional):

bash
Copy
Edit
python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Streamlit app:

bash
Copy
Edit
streamlit run app.py
📁 Project Structure
bash
Copy
Edit
diabetes_prediction_app/
│
├── app.py                 # Streamlit app
├── model.pkl              # Trained ML model
├── requirements.txt       # Project dependencies
├── README.md              # Project overview
└── assets/
    └── screenshot.png     # App UI image
📈 Model Info
Dataset: Pima Indians Diabetes Dataset

Model Used: Logistic Regression / RandomForestClassifier

Accuracy: ~78% (you can tune or improve this!)

📄 License
This project is licensed under the MIT License.

🙌 Acknowledgements
Dataset: UCI Machine Learning Repository

Streamlit for making ML app deployment super easy!


