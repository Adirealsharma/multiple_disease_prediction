This README provides a clear overview, setup instructions, and usage guidelines:

---

# Multiple Disease Prediction Web App

This is a **Streamlit-based web application** that predicts the likelihood of various diseases using machine learning models. The application supports prediction for:

* Diabetes
* Heart Disease
* Parkinson's Disease

## 🚀 Live Demo

> yet to host

---

## 🧠 Features

* Separate machine learning models trained for each disease
* User-friendly web interface using Streamlit
* Interactive forms for each disease input
* Real-time prediction based on user input
* Modular and well-organized codebase

---

## 📁 Project Structure

```
multiple_disease_prediction/
│
├── diabetes_model.sav            # Trained model for diabetes prediction
├── heart_disease_model.sav       # Trained model for heart disease prediction
├── parkinsons_model.sav          # Trained model for Parkinson's disease prediction
│
├── app.py # Streamlit frontend app
│
├── README.md                     # Project documentation
└──
```

---

## 🛠️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/siddhardhan23/multiple-disease-prediction-streamlit-app.git
cd multiple-disease-prediction-streamlit-app
```

### 2. Create and Activate a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit App

```bash
streamlit run multiple_disease_prediction.py
```

The app will open in your browser at `http://localhost:8501`.

---

## 📊 Models Used

* **Diabetes Prediction**: Trained using Pima Indians Diabetes Dataset.
* **Heart Disease Prediction**: Trained on Cleveland Heart Disease Dataset.
* **Parkinson’s Disease Prediction**: Trained using the UCI Parkinson’s dataset.

Models are serialized using **`joblib`** and loaded during app runtime.

---

## 💡 Usage

1. Choose the disease you want to check from the sidebar.
2. Enter the required medical parameters in the form.
3. Click "Predict" to see the result.

---

## 📌 Requirements

* Python 3.7+
* Streamlit
* scikit-learn
* pandas
* numpy

(Full list in `requirements.txt`)

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/siddhardhan23/multiple-disease-prediction-streamlit-app/blob/main/LICENSE) file for details.

---

## 🙌 Acknowledgements

* Streamlit for the UI framework
* UCI Machine Learning Repository for datasets

---


# multiple_disease_prediction
