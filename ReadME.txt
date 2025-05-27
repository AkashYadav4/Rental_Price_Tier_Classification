## 🏠 Rental Price Tier Classification

A machine learning project to classify rental apartment listings into **Low**, **Medium**, and **High** pricing tiers using real-world data and multiple supervised learning models.

---

## 📁 Project Structure

```
📊 rentalApartments_data.csv         → Original dataset  
🧼 cleanedApartments_data.xlsx       → After cleaning + preprocessing  
📉 FinalApartments_data.csv          → Final dataset (after outlier handling)

📒 rentalAnalysis.ipynb              → Data cleaning, preprocessing  
📒 rentalprice-visualization.ipynb   → EDA (visualizations & plots)  
📒 outlier_handling.ipynb            → Outlier detection & treatment  

📒 Random_Forest_and_Decision_Tree.ipynb  
📒 Naive_Bayes_and_AdaBoost.ipynb    
📒 Logistic_Regression.ipynb         
📒 KNN.ipynb                          → Model training & evaluation  

📁 project_visualization/            → Confusion matrix, ROC, importance plots  
📄 Rental_Price_Tier_Classification_Report.pdf  
🎓 RentalPriceTierClassification.pptx  
```

---

## 🔍 Project Overview

We built and evaluated classification models to predict rental price tiers based on features like:
- Square footage
- Number of bedrooms & bathrooms
- Amenities
- Neighborhood/city

---

## 📦 Models Used

- **K-Nearest Neighbors (KNN)**
- **Random Forest & Decision Tree**
- **Logistic Regression**
- **Naive Bayes**
- **AdaBoost**

Each model was evaluated using:
- Confusion Matrix
- ROC-AUC Curve
- Classification Report
- Cross-Validation Accuracy

---

## 📈 Workflow Breakdown

| Step                        | Notebook                         | Description                                      |
|-----------------------------|----------------------------------|--------------------------------------------------|
| Data Cleaning               | `rentalAnalysis.ipynb`           | Imputation, transformations, type conversion     |
| EDA                         | `rentalprice-visualization.ipynb`| Distributions, correlations, pair plots          |
| Outlier Handling            | `outlier_handling.ipynb`         | Z-score/IQR, visual checks                       |
| Model Training              | See individual model notebooks   | Each model has its own `.ipynb` with metrics     |
| Final Evaluation            | Visuals in `project_visualization/` | Confusion matrix, ROC, feature importances   |

---

## 🧠 Key Highlights

- Applied **SMOTE** to balance class distribution
- Performed **feature scaling** & **label encoding**
- Used **GridSearchCV** for model optimization
- Reduced dimensionality using **PCA**
- Delivered clean visual comparisons across models

---

## 🛠️ Tech Stack

- **Python 3**
- **scikit-learn**
- **pandas, numpy**
- **seaborn, matplotlib**
- **imbalanced-learn**
- **Jupyter Notebook**

---

## 🏁 How to Run

1. Clone the repo:
```bash
git clone https://github.com/AkashYadav4/rental-price-tier-classification.git
cd rental-price-tier-classification
```

2. (Optional) Create virtual environment:
```bash
python -m venv venv
source venv/bin/activate   # or venv\Scripts\activate on Windows
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Launch notebooks in Jupyter:
```bash
jupyter notebook
```

✅ Before running, **ensure file paths in code match your local directory structure.**

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙋‍♂️ Author

**Akash Kumar Yadav**  
MS in Computer Science, Fordham University  
🔗 [LinkedIn](https://www.linkedin.com/in/akash-yadav-66b211180/) | 🖥️ [GitHub](https://github.com/AkashYadav4)
