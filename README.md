# 🏡 House Price Prediction

This project uses **Linear Regression** on the **Boston Housing Dataset** to predict house prices.  
It also includes an interactive **Streamlit web app** for making single and batch predictions.

---

## ✨ Features
- 📊 Predict house prices using **Linear Regression**
- 🌐 Interactive **Streamlit UI**
- 📂 Supports **single input** and **CSV batch predictions**
- ⚡ Handles both numerical & categorical features efficiently  

---

## 📂 Dataset
The project uses the **Boston Housing Dataset**, which includes features such as:  
- `CRIM` – Crime rate  
- `ZN` – Proportion of residential land zoned for large lots  
- `INDUS` – Proportion of non-retail business acres per town  
- `CHAS` – Charles River dummy variable  
- `NOX` – Nitric oxides concentration  
- `RM` – Average number of rooms per dwelling  
- `AGE` – Proportion of owner-occupied units built before 1940  
- `DIS` – Weighted distances to employment centers  
- `RAD` – Index of accessibility to radial highways  
- `TAX` – Property-tax rate  
- `PTRATIO` – Pupil-teacher ratio  
- `B` – Proportion of Black residents  
- `LSTAT` – Percentage of lower status population  

---

## 🛠️ Tech Stack
- **Python** 3.8+  
- **Streamlit** – for interactive UI  
- **Scikit-learn** – for machine learning model  
- **Pandas & NumPy** – for data preprocessing  

---
## 📂 Project Structure
House_Price_Prediction/
│── app.py                     # Streamlit application
│── HousingData.csv            # Dataset
│── boston_linear_regression.pkl # Trained model
│── linear_feature_meta.json   # Metadata for features
│── requirements.txt           # Dependencies
│── README.md                  # Project documentation
---

## ▶️ Installation & Running the Project

### 1. Clone the repository
git clone https://github.com/Manasa-Raghavendra/House_Price_Prediction.git
cd House_Price_Prediction

### 2. Create a virtual environment (recommended)
python -m venv venv
# On Linux/Mac
source venv/bin/activate
# On Windows
venv\Scripts\activate

### 3. Install dependencies
pip install -r requirements.txt

If you don’t have a requirements.txt file, install manually:
pip install streamlit scikit-learn pandas numpy

### 4. Run the Streamlit app
streamlit run app.py

After running, open the local URL shown in the terminal (default: http://localhost:8501) to access the app.

---

## 📊 Example Usage
- Enter housing feature values manually for **single prediction**.  
- Upload a CSV file for **batch predictions**.  

---

## 👩‍💻 Author
**Manasa Raghavendra**  
Department of Artificial Intelligence  
Maharaja Institute of Technology, Mysore  

GitHub: https://github.com/Manasa-Raghavendra

---

Maharaja Institute of Technology, Mysore

GitHub: Manasa-Raghavendra
