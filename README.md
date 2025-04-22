# Customer-Behaviour-Prediction-202401100300198

This project aims to classify customers as Bargain Hunters or Premium Buyers based on their purchase history. It uses a simple logistic regression model trained on customer behavior data such as total spending, average purchase amount, and visit frequency.

 Project Overview
Businesses can significantly benefit from understanding their customer segments. By categorizing users into bargain-focused or premium-oriented, they can:

Target promotions effectively

Customize offers

Improve customer satisfaction

This machine learning model helps automate that classification using basic behavioral metrics.

Features Used
total_spent: Total amount spent by the customer

avg_purchase_value: Average amount spent per purchase

visits_per_month: Number of visits per time period

buyer_type: Target label (0 for Bargain Hunter, 1 for Premium Buyer)

Technologies & Libraries
Python

Pandas

NumPy

Matplotlib

Scikit-learn

Folder Structure

📦customer-behavior-prediction/
 ┣ 📄 customer_data.csv         # Customer dataset
 ┣ 📄 customer_prediction.py    # Main Python script with training, testing, and visualization
 ┣ 📄 README.md                 # Project documentation

 How to Run the Project
Clone this repository:


git clone https://github.com/yourusername/customer-behavior-prediction.git
cd customer-behavior-prediction
Install required libraries:
pip install pandas numpy matplotlib scikit-learn
Run the main script:

python customer_prediction.py

Output:

Confusion matrix and classification report

Scatter plot showing customer segmentation

SAMPLE OUTPUT
Confusion Matrix:
[[4 0]
 [1 3]]

Classification Report:
               precision    recall  f1-score   support

Bargain Hunter     0.80      1.00      0.89         4
Premium Buyer      1.00      0.75      0.86         4
 
 References
Pandas Documentation

Scikit-learn Docs

Matplotlib Docs

Dataset: "internally generated"

Author
Ridhima Goyal
Feel free to connect or collaborate!
