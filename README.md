# 🏠 House Price Prediction App

A machine learning project that predicts house prices based on property features such as location, area, number of rooms, and amenities. The model uses regression techniques to provide accurate price estimates and is deployed as an interactive web application using Streamlit.

---

## 📌 Features
- **Data Preprocessing** – Handles missing values, encodes categorical features, and scales numerical data.
- **Model Training** – Trains multiple regression models (Linear Regression, Random Forest, XGBoost) and selects the best one based on evaluation metrics.
- **Interactive Web App** – Built with Streamlit for real-time predictions.
- **Model Persistence** – Saves the trained model using `joblib` for easy deployment.
- **Visualizations** – Displays data distribution, correlations, and feature importance.

---

## 📊 Tech Stack
- **Python** (pandas, numpy, scikit-learn, xgboost)
- **Streamlit** for the web app
- **Matplotlib / Seaborn** for visualizations
- **Joblib** for model saving/loading

---

## 📂 Project Structure
house-price-prediction/
│── data/ # Dataset files
│── notebooks/ # Jupyter notebooks for exploration
│── app.py # Streamlit app
│── model/ # Saved trained model
│── requirements.txt # Project dependencies
│── README.md # Project documentation

---

## 🚀 Installation & Usage
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/house-price-prediction.git
   cd house-price-prediction

pip install -r requirements.txt
streamlit run app.py
Navigate to http://localhost:8501 to interact with the app.

## 📈 Example Prediction
**Inputs**: Location: Cairo, Area: 120 sqm, Bedrooms: 3, Bathrooms: 2, Amenities: Parking & Garden

**Output**: Estimated Price: EGP 1,250,000

## 📜 License
This project is licensed under the MIT License.

## 🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


---
## 🔗 Links 
If you want, I can also give you **`app.py` code** so you have something to upload directly to GitHub without needing to build it from scratch.    

Do you want me to prepare that next?
