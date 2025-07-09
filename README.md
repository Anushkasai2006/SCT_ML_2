# SCT_ML_2
To create a K-means clustering algorithm for Customer Segmentation
# 🎯 Task 2: Customer Segmentation using K-Means Clustering

This project segments retail store customers based on their purchase behavior and demographics using unsupervised learning.

## 📌 Objective
Use K-Means clustering to group customers into meaningful segments based on:
- Gender
- Age
- Annual Income (in ₹ Lakhs)
- Spending Score (1–100)

## 🧠 Technologies Used
- Python
- Pandas and NumPy
- Scikit-learn (KMeans, StandardScaler)
- Matplotlib and Seaborn
- Gradio for deployment

## ⚙️ Approach
- Loaded and preprocessed the Mall Customers dataset
- Encoded categorical features (e.g., Gender)
- Scaled numerical data using StandardScaler
- Used the Elbow Method to choose the optimal number of clusters (k=5)
- Applied K-Means to form 5 distinct customer groups
- Assigned friendly names to each cluster for clarity:
  - 🎯 Young High Spenders
  - 🛑 Wealthy but Cautious
  - 🎉 Impulsive Spenders
  - 🧓 Mature Mid Spenders
  - ⚖️ Balanced Shoppers

## 🖥️ Gradio Interface
An interactive UI was developed using Gradio to predict the customer segment based on user input.

### ✅ Example Input
| Gender | Age | Annual Income (₹ Lakhs) | Spending Score | Segment                       |
|--------|-----|--------------------------|----------------|-------------------------------|
| Male   | 22  | 3                        | 90             | 🎯 Young High Spenders        |
| Female | 40  | 10                       | 20             | 🛑 Wealthy but Cautious       |
| Female | 21  | 1.5                      | 95             | 🎉 Impulsive Spenders         |

## 📦 Output
Instead of raw cluster numbers, user-friendly labels are returned with brief descriptions.

---

📂 This project was developed as part of my AI Agent Development internship.
