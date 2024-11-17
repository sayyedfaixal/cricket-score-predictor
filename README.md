# 🏏 Cricket Score Predictor App 🏆

This repository contains a **Cricket Score Predictor** built using **T20 World Cup data**. The app uses **machine learning** to predict the final score of a team based on the current match scenario. It's a fun and insightful tool for cricket enthusiasts to get a sense of how the game might unfold! 🌟

## 📋 Features

- Predicts the final score of the batting team in a T20 cricket match.
- User-friendly interface powered by **Streamlit**.
- Uses key match details like current score, overs, and wickets for prediction.
- Includes city and team-specific data for better accuracy.

---

## 🛠️ Technologies Used

- **Python** 🐍
- **Streamlit** for web interface 🌐
- **Pandas** and **NumPy** for data processing 📊
- **XGBoost** for machine learning 💡
- **Scikit-learn** for metrics and preprocessing 📏
- **Pickle** for saving and loading models 🛠️

---

## 🚀 How to Run the App

Follow these steps to get the app up and running:

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/cricket-score-predictor.git
cd cricket-score-predictor
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Prepare the Model

Ensure the pipe.pkl file (trained model) is in the project directory. If not, train the model or place the existing pipe.pkl file in the root folder.

### 4️⃣ Run the App

Start the Streamlit app using:

```bash
streamlit run app.py
```

### 5️⃣ Interact with the App

- Open the URL provided in your terminal (typically http://localhost:8501).
- Select teams, city, current score, overs completed, wickets fallen, and runs scored in the last 5 overs.
- Click Predict Score to get the estimated final score! 🎯

### 📂 Folder Structure

```
cricket-score-predictor/
├── app.py               # Streamlit application
├── pipe.pkl             # Trained ML model
├── requirements.txt     # Dependencies
├── README.md            # This file
```
