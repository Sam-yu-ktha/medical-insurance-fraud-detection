# 🏥 Medical Insurance Fraud Detection System

## 📌 Project Description

The **Medical Insurance Fraud Detection System** is a Big Data Analytics application developed using **PySpark** and **Machine Learning**.

This system analyzes medical insurance claim data to identify potentially fraudulent claims using a **Random Forest Classifier**. It also provides an interactive analytics dashboard and real-time fraud prediction interface.

---

## 🚀 Key Features

### 📊 Data Processing
- Load CSV dataset into PySpark
- Big data processing using Apache Spark
- Fraud statistics calculation
- SQL-based query execution

### 🔎 Search & Query
- Search by Claim ID
- Search by Patient Name
- Search by Hospital
- Search by Disease
- Custom SQL queries support

### 📈 Analytics Dashboard
- Fraud vs Non-Fraud distribution
- Claim amount comparison
- Top diseases involved in fraud
- Age-based fraud analysis
- Interactive Plotly visualizations

### 🤖 Machine Learning Module
- Random Forest Classifier
- Feature encoding
- Confusion Matrix generation
- Feature importance analysis
- Accuracy calculation

### ⚡ Fraud Prediction
- Real-time fraud probability prediction
- Risk classification (Low / Medium / High)
- Historical similar claim analysis
- Recommendation for approval or manual review

---

## 🧠 Technologies Used

- Python  
- Apache Spark (PySpark)  
- Scikit-learn  
- Gradio  
- Plotly  
- Pandas  
- NumPy  

---

## 📂 Project Structure

medical-insurance-fraud-detection/
│
├── app.py
├── Medical_Insurance_Fraud_Detection.ipynb
├── requirements.txt
├── README.md
├── .gitignore
└── insurance_data.csv (optional)

---

## 📊 Dataset Format (Required)

The uploaded CSV file **must contain the following exact column names**:

| Column Name      | Description |
|------------------|------------|
| Claim_ID        | Unique claim identifier |
| Patient_Name    | Name of the patient |
| Age             | Patient age (integer) |
| Disease         | Disease type (string) |
| Claim_Amount    | Insurance claim amount (numeric) |
| PotentialFraud  | Fraud label (0 = No, 1 = Yes) |
| Hospital        | Hospital name |

⚠️ Column names are **case-sensitive** and must match exactly.

---

## ▶️ How to Run

### 1️⃣ Install Required Libraries

```bash
pip install -r requirements.txt

### 2️⃣ Run the Application

python app.py

### 3️⃣ Upload Dataset

Upload a properly formatted CSV file (as described above) into the application interface.

📈 Output

The system:

Detects fraudulent insurance claims

Displays fraud probability

Generates an interactive analytics dashboard

Provides risk-based recommendations

👩‍💻 Author

Samyuktha R

📜 License

This project is developed for academic purposes and is licensed under the MIT License.
