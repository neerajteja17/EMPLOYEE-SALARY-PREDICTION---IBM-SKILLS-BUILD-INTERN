# 🧠 Employee Salary Prediction

This project aims to predict whether an individual's income exceeds $50K/year based on various features such as education, workclass, hours per week, etc. The model is built using classification algorithms and visualized using an interactive web interface.

---

## 📁 Project Structure

```
├── model_training.ipynb     # Jupyter notebook for data preprocessing and model building
├── best_model.pkl           # Trained and serialized ML model
├── gradio_app.py            # Gradio interface for model prediction
├── streamlit_app.py         # Optional Streamlit interface
├── requirements.txt         # Required Python packages
└── README.md                # Project overview and usage instructions
```

---

## 🔧 Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/employee-salary-prediction.git
cd employee-salary-prediction
```

2. Create a virtual environment and activate it:
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

3. Install the required libraries:
```bash
pip install -r requirements.txt
```

---

## 🚀 How to Run

### Option 1: Run Gradio Web App
```bash
python gradio_app.py
```

### Option 2: Run Jupyter Notebook
```bash
jupyter notebook model_training.ipynb
```

### Option 3: Run Streamlit App
```bash
streamlit run streamlit_app.py
```

---

## 📊 Dataset

- Source: [UCI Adult Census Dataset](https://archive.ics.uci.edu/ml/datasets/adult)
- Features include: age, workclass, education, marital-status, occupation, etc.
- Target: Income class (<=50K or >50K)

---

## ✅ Features

- Logistic Regression and Decision Tree models
- Model accuracy ~85%
- Interactive web interface (Gradio)
- Clear preprocessing and feature engineering steps

---

## 🛠️ Tools & Libraries

- Python
- Pandas, NumPy, Scikit-learn
- Gradio, Streamlit
- Joblib

---

## 🤖 Future Improvements

- Add more classification models (Random Forest, XGBoost)
- Improve accuracy with hyperparameter tuning
- Use cross-validation and ROC-AUC
- Deploy with Docker or cloud platforms

---

## 🧑‍💻 Author

- **Your Name** – [yourgithub](https://github.com/yourusername)

---

## 📄 License

This project is licensed under the MIT License.
