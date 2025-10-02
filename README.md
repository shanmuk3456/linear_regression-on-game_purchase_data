
# Linear Regression Project

This repository contains a Jupyter Notebook that demonstrates **Linear Regression** using Python and popular data science libraries.  
The project focuses on data preprocessing, exploratory data analysis (EDA), and building a predictive model with `scikit-learn`.

---

## 📂 Dataset
The dataset used in this project is included in the repository.  
 
**Description:** Contains user-related features (such as purchase history, spending, etc.) that are used to predict target values.  

### 📊 Sample Data Preview
| UserID                               | Age | Gender | Country     | Device  | GameGenre     | SessionCount | AverageSessionLength | SpendingSegment | InAppPurchaseAmount | FirstPurchaseDaysAfterInstall | PaymentMethod | LastPurchaseDate |
| ------------------------------------ | --- | ------ | ----------- | ------- | ------------- | ------------ | -------------------- | --------------- | ------------------- | ----------------------------- | ------------- | ---------------- |
| c9889ab0-9cfc-4a75-acd9-5eab1df0015c | 49  | Male   | Norway      | Android | Battle Royale | 9            | 12.83                | Minnow          | 11.4                | 28                            | Apple Pay     | 2025-03-19       |
| 7c9e413c-ecca-45f2-a780-2826a07952a2 | 15  | Male   | Switzerland | iOS     | Action RPG    | 11           | 19.39                | Minnow          | 6.37                | 18                            | Debit Card    | 2025-06-08       |
| fd61e419-1a92-4f43-a8c7-135842ad328a | 23  | Male   | China       | Android | Fighting      | 9            | 8.87                 | Minnow          | 15.81               | 30                            | Apple Pay     | 2025-06-02       |
| bdb7f6d1-ff9a-468c-afe7-43f32a94293e | 31  | Male   | Mexico      | Android | Racing        | 12           | 19.56                | Minnow          | 13.49               | 9                             | Debit Card    | 2025-04-01       |


---

## 📌 Features
- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA) with `pandas`, `matplotlib`, and `seaborn`  
- Implementation of **Linear Regression** using `scikit-learn`  
- Evaluation of the model using performance metrics  

---

## 📂 Repository Structure
Linear-Regression-Project/
│
├── mobile_game_inapp_purchases.csv    # Dataset used for training and testing
├── Linear_regression.ipynb            # Jupyter Notebook with implementation
├── README.md                          # Project documentation



