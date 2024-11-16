# AgroGrow - Crop Prediction System 🌾

AgroGrow is a machine learning-based system designed to assist farmers and agricultural enthusiasts in identifying the most suitable crop to grow based on soil and environmental conditions. By leveraging data-driven insights, AgroGrow empowers users to make informed decisions, improving productivity and sustainability.

---

## Features 🚀

- **Accurate Crop Recommendations**: Predicts the most suitable crop based on key environmental parameters.
- **Interactive Web Interface**: Dynamically input data via a user-friendly website.
- **Multi-Model Approach**: Employs Logistic Regression, Random Forest, and Support Vector Machines (SVC) for high accuracy.
- **Scalable Solution**: Easily adaptable to include additional parameters or datasets.

---

## Dataset 📊

This project utilizes the **Crop Recommendation Dataset** from Kaggle. The dataset includes the following features:
- **N, P, K**: Soil macronutrients (Nitrogen, Phosphorus, Potassium).
- **Temperature**: Average temperature (°C).
- **Humidity**: Percentage of humidity.
- **pH**: Acidity or alkalinity of the soil.
- **Rainfall**: Annual rainfall (mm).
- **Label**: Crop type.

🔗 [Crop Recommendation Dataset on Kaggle](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset)

---

## Technologies Used 🛠️

- **Frontend**: HTML, CSS
- **Backend**: Flask
- **Libraries**:
  - Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

---

## How It Works 🤖

1. **Data Input**: Users input soil and environmental parameters (N, P, K, temperature, humidity, pH, rainfall) via the web interface.
2. **Model Prediction**: The input data is fed into trained machine learning model.
3. **Output**: The system predicts the most suitable crop to grow based on the input parameters.

---

## Installation and Usage 📥

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Rohit15504/AgroGrow---Crop-Predictions-System.git
   cd AgroGrow---Crop-Predictions-System
   ```
2. **Install dependencies:**

```bash
pip install -r requirements.txt
 ```
3. **Run the application:**

```bash
python app.py
 ```

4. **Access the web application at:**

```bash
http://127.0.0.1:5000/
 ```
  ## Acknowledgments 🙏

- [Kaggle](https://www.kaggle.com/) for providing the dataset.
- Machine Learning resources from [Scikit-learn Documentation](https://scikit-learn.org/).
