# Linear-Regression-Assignment

## 📌 Project Overview
This project uses **Linear Regression** to analyze customer behavior and predict how much a customer spends yearly based on their interaction with an e-commerce platform.

The goal is to understand which factors influence spending the most and help the company make better business decisions.

---

## 📊 Dataset
The dataset used is **Ecommerce Customers**, which includes the following features:

- Avg. Session Length  
- Time on App  
- Time on Website  
- Length of Membership  
- Yearly Amount Spent (Target Variable)  

Some columns such as Email, Address, and Avatar were excluded since they are not useful for prediction.

---

## ⚙️ Steps Performed

1. Loaded and explored the dataset using Pandas  
2. Performed data visualization using:
   - Jointplots  
   - Pairplots  
3. Selected relevant numerical features  
4. Split the data into training and testing sets  
5. Trained a Linear Regression model  
6. Generated predictions on test data  
7. Evaluated model performance using error metrics  

---

## 🧠 Model
The model used:
- Linear Regression (from Scikit-learn)

Target variable:
- `Yearly Amount Spent`

---

## 📈 Results & Insights

- **Length of Membership** has the strongest impact on yearly spending  
- **Time on App** has a higher impact than Time on Website  

### 💡 Conclusion
Customers who stay longer with the company and spend more time on the mobile app tend to spend more money.

This suggests that the company should focus more on improving the **mobile app experience** rather than the website.

---

## 🛠️ Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---
