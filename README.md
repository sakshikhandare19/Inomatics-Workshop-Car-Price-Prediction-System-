# 🚘 Car Price Prediction System  
### End-to-End Machine Learning Pipeline with Deployment

---

## 📖 About the Project

This project implements a complete Machine Learning pipeline to predict car prices based on various vehicle attributes. The model is built using **Linear Regression** and deployed as an interactive web application using **Streamlit**.

The objective is to demonstrate practical understanding of:

- Data preprocessing
- Feature engineering
- Model training & evaluation
- Deployment of ML models

---

## 🎯 Business Objective

The automobile resale market relies heavily on pricing accuracy.  
Incorrect price estimation can lead to financial losses for sellers and buyers.

This system predicts the **estimated resale price of a car** based on:

- Brand
- Year of Manufacture
- Fuel Type
- Transmission Type
- Mileage
- Engine Capacity
- Ownership Status

---

## ⚙️ Machine Learning Pipeline

### 🔹 Data Preprocessing
- Handling missing values
- Removing duplicates
- Encoding categorical variables
- Feature scaling
- Outlier detection

### 🔹 Exploratory Data Analysis
- Correlation heatmap
- Distribution analysis
- Feature-target relationship analysis
- Multicollinearity check

### 🔹 Model Building
- Algorithm Used: **Linear Regression**
- Train-Test Split
- Model fitting on training data
- Residual analysis

### 🔹 Model Evaluation

Performance evaluated using:

- R² Score  
- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)

---

## 🚀 Deployment

The trained model is integrated into a **Streamlit web application** that allows users to:

- Input car specifications
- Get instant price prediction
- Interact with a clean and intuitive UI

---

## 🧰 Tech Stack

| Category | Tools Used |
|----------|------------|
| Programming | Python |
| Data Handling | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Deployment | Streamlit |

---

## 📂 Directory Structure

```
car-price-prediction/
│
├── dataset.csv
├── model.pkl
├── app.py
├── notebook.ipynb
├── requirements.txt
└── README.md
```

---

## 🔧 Installation Guide

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/car-price-prediction.git
cd car-price-prediction
```

### Step 2: Create Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Run the Application

```bash
streamlit run app.py
```

---

## 📊 Sample Prediction Flow

1. User enters vehicle details.
2. Input data is preprocessed.
3. Trained Linear Regression model predicts price.
4. Predicted price is displayed instantly.

---

## 📌 Key Takeaways

- Built a complete ML pipeline from scratch.
- Understood regression modeling and evaluation.
- Learned practical deployment using Streamlit.
- Bridged theoretical ML concepts with real-world implementation.

---

## 🔮 Future Enhancements

- Implement Ridge & Lasso Regression
- Add Hyperparameter Tuning
- Use Ensemble Models (Random Forest, XGBoost)
- Deploy on Cloud (AWS / Render / Heroku)
- Add Model Monitoring

---

## 📜 Disclaimer

This project was developed for educational purposes during a Machine Learning workshop.

---

## 👩‍💻 Author

Developed as part of an ML workshop conducted by Innomatics Research Labs.
