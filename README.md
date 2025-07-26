# Project-Customer_Shopping_Data_Clustering

🛍 Customer Segmentation Using KMeans Clustering

This project applies KMeans clustering to segment customers based on their shopping behavior. It helps identify customer groups like high spenders, loyal buyers, or low-engagement customers using unsupervised machine learning.


---
📌 Objectives

Segment customers based on shopping behavior

Identify patterns in purchase amount, age, review rating, and purchase frequency

Build a Streamlit web app to predict customer cluster using user input



---

📊 Dataset Overview

Total Records: 3,900

Features Used:

Age

Purchase Amount (USD)

Review Rating

Previous Purchases




---

⚙ Technologies Used

Python

Pandas, NumPy

Scikit-learn (KMeans, StandardScaler)

Streamlit (for web app)

Pickle (for model serialization)



---

🧠 ML Approach

1. Feature Selection: Choose relevant numerical features


2. Preprocessing: Scale features using StandardScaler


3. Clustering: Apply KMeans with n_clusters=5


4. Prediction: Accept user input and classify into a cluster


5. Deployment: Create a Streamlit web interface for predictions




---

📦 Files Included

customer_shopping_data.csv – Dataset

train_model.py – Trains KMeans and saves the model & scaler

Customer_Clustering_Model.pkl – Saved model

app.py – Streamlit app for live predictions



---

🚀 How to Run

1. Install packages:

pip install pandas numpy scikit-learn streamlit


2. Train model:

python train_model.py


3. Run app:

streamlit run app.py




---

🧪 Sample Inputs to Try

Age	Purchase	Rating	Previous Purchases

22	150	4.5	0
45	900	3.2	8
35	400	4.2	5


> Try different values in the app to see which cluster they belong to.




---

📈 Output

The app will return the cluster number (0 to 4) indicating the customer segment. Each cluster groups customers with similar shopping behavior.
![WhatsApp Image 2025-07-26 at 21 38 16_c2bb8ab4](https://github.com/user-attachments/assets/7a8ecd96-71da-4d86-ab0c-6c5675c941c2)



---

✅ Future Improvements

Label clusters (e.g. High-Value, Budget, One-Time Buyer)

Add visualizations for each cluster

Use more features (location, product category, etc.)

Deploy app online (Streamlit Cloud / Hugging Face Spaces)



---

