# Customer-Behavior-Prediction_202401100300158-
# 🧠 Customer Behavior Prediction

This project builds a machine learning model to classify customers into two categories — **Bargain Hunter** or **Premium Buyer** — based on their shopping behavior. It uses a Random Forest Classifier to make predictions based on features like total spending, average purchase value, and visit frequency.

---

## 📌 Problem Statement

Understanding customer behavior is crucial for targeted marketing and personalized services. This project aims to predict customer types using their behavioral data, enabling businesses to better tailor their strategies.

---

## 📂 Dataset

The dataset used (`customer_behavior.csv`) contains the following columns:

- `total_spent`: Total money spent by the customer  
- `avg_purchase_value`: Average value of each purchase  
- `visits_per_month`: Number of visits the customer makes per month  
- `buyer_type`: Label indicating the type of buyer (bargain hunter or premium buyer)

---

## 🧰 Technologies Used

- Python  
- Pandas  
- Matplotlib & Seaborn (for visualization)  
- Scikit-learn (for machine learning)

---

## 🧪 Methodology

1. **Data Preprocessing**  
   - Encoded categorical labels into numeric form using `LabelEncoder`.

2. **Feature Selection**  
   - Selected relevant columns as features: `total_spent`, `avg_purchase_value`, `visits_per_month`.

3. **Model Training**  
   - Used `RandomForestClassifier` from `scikit-learn`.

4. **Evaluation**  
   - Evaluated using Accuracy, Precision, Recall, and a Confusion Matrix.

---

## 📊 Model Performance

- **Accuracy**: 0.85  
- **Precision**: 0.88  
- **Recall**: 0.83  

These metrics indicate that the model performs well in correctly identifying the customer category.

---

## 📉 Visualization

A confusion matrix is plotted to visualize the model's prediction performance:

![Confusion Matrix](./path_to_your_screenshot.png)

> Replace `path_to_your_screenshot.png` with the actual path or GitHub-hosted image link if available.

---

## 🚀 Potential Improvements

- Tune hyperparameters for better model accuracy  
- Add more features (e.g., demographics, device usage)  
- Try other classification models like XGBoost or Logistic Regression for comparison

---

## 📝 How to Run

1. Clone the repository  
2. Make sure `customer_behavior.csv` is in the same directory  
3. Run the Python script using:

```bash
python customer_behavior_prediction.py
