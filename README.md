Preview - https://euwkwzdz8sodqwb6b8gzlh.streamlit.app/

# 🌧️ Rainfall Prediction Web App

This is a Machine Learning-based web application that predicts **the possibility of rainfall** using a trained ML model. The app is built with **Python**, **Flask**, and a clean **HTML frontend**, powered by a dataset and pre-trained model saved as a `.pkl` file.

---

## 📂 Project Structure

```
rainfall-prediction/
│
├── dataset.csv             # Dataset used to train the model
├── model.pkl               # Trained model file (pickle)
├── app.py                  # Flask backend application
├── requirements.txt        # Python dependencies
├── templates/
│   └── index.html          # Frontend HTML form
├── static/
│   └── style.css           # Optional CSS for styling
└── README.md               # Documentation file
```

## 🚀 Features

- Predicts rainfall using a trained ML model
- Simple and interactive web interface
- Easy to run locally or deploy online
- Trained on real-world weather dataset


## ⚙️ Tech Stack

- **Frontend**: HTML, CSS
- **Backend**: Flask (Python)
- **ML Model**: Scikit-learn
- **Others**: Pandas, NumPy, Pickle


## 🔧 How to Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/rainfall-prediction.git
cd rainfall-prediction
```

### 2. Install Dependencies

Make sure you have Python 3.8+ installed. Then run:

```bash
pip install -r requirements.txt
```

### 3. Run the App

```bash
python app.py
```

Visit: **http://localhost:5000** in your browser.

---

## 🧠 About the Model

- Trained using: `RandomForestClassifier` *(or specify your model here)*
- Input features may include: temperature, humidity, wind speed, pressure, etc.
- Output: Probability of rainfall (Yes/No)

---

## 🌍 Deploy on Render (Free Hosting)

You can host this Flask app on **Render**:

### Steps:
1. Create a free account at [https://render.com](https://render.com)
2. Connect your GitHub repo
3. Create a new **Web Service**
4. Set build command to:

```bash
pip install -r requirements.txt
```

5. Set start command to:

```bash
python app.py
```

6. Add `model.pkl`, `dataset.csv`, and other files in root

---

## 🌐 Optional Deployment on Replit

1. Go to [https://replit.com](https://replit.com)
2. Import GitHub repo
3. Install dependencies manually or via `replit.nix`
4. Hit "Run"


## 👨‍💻 Developed By

**Aashish Vishal Bhabal**  
📧 aashishxcode@gmail.com

---

## 📄 License

This project is licensed under the **MIT License** – feel free to use, modify, and share.

---

## 💡 Suggestions

If you have ideas for improvements or spot any bugs, feel free to open an issue or pull request. Contributions are welcome!

```


