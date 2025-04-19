#  Medical Recommendation System

An end-to-end Medical Recommendation System built using **Python** and **Machine Learning**. This project takes user-inputted symptoms and predicts the most likely disease, then recommends medications, precautions, workouts, diets, and more through a simple web interface.

---

## Features

- Predict disease from user-inputted symptoms
- Recommend:
  - Medications
  - Precautions
  - Workout tips
  - Diet plans
  - Disease description
- Clean and user-friendly web interface
- Modular and extensible codebase

---

## 🛠 Tech Stack

- **Python**
- **Scikit-learn** – ML model
- **Pandas, NumPy** – Data processing
- **Flask** – Web framework
- **HTML/CSS** – Frontend
- **SQLite / CSV** – Data source for recommendations

---

## 🚀 How It Works

1. User enters symptoms in the search bar.
2. Symptoms are passed to a trained ML model.
3. The model predicts the disease.
4. Matching recommendations are fetched from a database.
5. Results are displayed on the frontend.

---

## 📸 Screenshots

_Add screenshots of the interface or system output here._

---

## 📽️ Demo

LinkedIn demo: 

---

## 📂 Installation

```bash
git clone https://github.com/yourusername/medical-recommendation-system.git
cd medical-recommendation-system
pip install -r requirements.txt
python app.py

📁 Project Structure

├── app.py
├── templates/
│   └── index.html
├── static/
│   └── style.css
├── model/
│   └── trained_model.pkl
├── data/
│   └── disease_database.csv
├── requirements.txt
└── README.md

