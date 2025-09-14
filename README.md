# 🏠 House Price Prediction  

This project predicts **Boston housing prices** using machine learning regression models.  
It provides both **single prediction** and **batch prediction (via CSV)** through an interactive **Streamlit web app**.  

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

## ▶️ Installation & Running the Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Manasa-Raghavendra/House_Price_Prediction.git
cd House_Price_Prediction
2️⃣ Create a virtual environment (recommended)
bash
Copy code
python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows
3️⃣ Install dependencies
bash
Copy code
pip install -r requirements.txt
If you don’t have a requirements.txt file, manually install dependencies:

bash
Copy code
pip install streamlit scikit-learn pandas numpy
4️⃣ Run the Streamlit app
bash
Copy code
streamlit run app.py
After running, open the local URL shown in the terminal (default: http://localhost:8501) to access the app.

📌 Author
👩‍💻 Manasa Raghavendra

Department of Artificial Intelligence

Maharaja Institute of Technology, Mysore

GitHub: Manasa-Raghavendra
