 Customer Lifetime Value (CLV) Prediction System

A machine learning-based web application that predicts **Customer Lifetime Value (CLV)**—the total revenue a business can expect from a customer over their entire relationship.

The system uses real-world transaction data, performs feature engineering (RFM analysis), and applies multiple machine learning models to estimate customer value and segment users for better business decisions.

---

 Features

- CLV Prediction using Machine Learning**
  - Linear Regression, Ridge, Lasso
  - Random Forest, Gradient Boosting

-  **Advanced Feature Engineering**
  - RFM Analysis (Recency, Frequency, Monetary)
  - Customer behavior metrics (tenure, purchase frequency, etc.)

-  **Interactive Dashboard**
  - Built using Streamlit
  - Real-time predictions and visual insights

-  **Customer Segmentation**
  - High, Medium, Low value customers
  - Actionable business strategies

-  **Feature Importance Analysis**
  - Understand what drives customer value

-  **Raw Data Exploration**
  - Analyze transactions, revenue trends, and customer behavior

---

##  Tech Stack

- **Python**
- **Pandas, NumPy**
- **Scikit-learn**
- **Matplotlib, Seaborn**
- **Streamlit**

---

##  Dataset

- UCI Online Retail Dataset
- Contains transactional data of customers across multiple countries
- Used to generate customer-level features and CLV

---

##  Installation & Setup

```bash
# Clone the repository
git clone https://github.com/shebasusan/Customer-lifetime-value-prediction-system

# Navigate to project folder
cd Customer-lifetime-value-prediction-system

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
