# Supply-chain-management-
# 📊 Kiddikind Millet Manufacturing Efficiency Analysis using Machine Learning

This repository contains the capstone project analyzing and optimizing manufacturing efficiency at **Kiddikind**, a millet-based health food company. By applying machine learning techniques on real-world manufacturing data, this study aims to enhance production performance, reduce waste, and provide valuable business insights.

---

## 📝 Abstract

This project explores **Kiddikind**, a company specializing in millet-based products, focusing on its manufacturing processes, health benefits of millets, and market positioning. Using advanced machine learning models, the project identifies operational inefficiencies and provides insights for optimization.

## 🧠 Key Objectives

- Analyze Kiddikind’s production and efficiency data
- Implement ML models for classification and prediction
- Evaluate and compare model performance
- Provide actionable insights to improve manufacturing efficiency

## 🧃 Company Overview: Kiddikind

Kiddikind is an innovative health-food brand committed to producing millet-based products that are:

- 🌾 Gluten-free  
- 🧠 Nutrient-rich (iron, fiber, protein)  
- 🌍 Environmentally sustainable  
- 👨‍👩‍👧‍👦 Designed for health-conscious families  

## 📚 Literature Support

The study is grounded in extensive literature on:

- Millet nutritional benefits  
- Sustainable food processing  
- Circular economy in agri-tech  
- Industrial millet processing and applications  

_References from Dovepress, Bhatty (1988), Devi et al. (2014), Patel & Sharma (2019), Rai et al. (2018) are included in the paper.

## 🔍 Methodology

### A. Data Collection & Preprocessing
- Collected key metrics: Production rate, energy usage, waste, quality score
- Normalization of features
- Missing values imputed using mean/median
- Data augmentation via synthetic noise for robust training

### B. Feature Extraction & Model Design
- **Feature Engineering:** Extracted from categorized efficiency levels
- **Models Used:**
  - Random Forest Classifier
  - SARIMA + Random Forest Hybrid
  - Gradient Boosting Classifier

### C. Training & Testing
- Train-test split with cross-validation
- Hyperparameter tuning
- Model visualization and result plotting

## 📈 Model Performance

| Model                         | Accuracy (%) |
|------------------------------|--------------|
| Random Forest Classifier     | 91.30%       |
| Hybrid SARIMA + RF           | 91.30%       |
| Gradient Boosting Classifier | 95.65% ✅     |

Other metrics used: Precision, Recall, F1-Score, MAE, RMSE, MAPE

## 🧪 Results

- Machine learning models effectively classify production efficiency.
- Gradient Boosting shows superior performance.
- Demonstrates potential for real-time decision-making in manufacturing.


## 🧾 Conclusion

This project highlights how AI can optimize production in millet manufacturing. It reduces manual labor, enhances prediction accuracy, and contributes to sustainable practices.

---

## 🚀 Future Scope

- Integrate transfer learning for cross-factory adaptability
- Apply explainable AI (XAI) to build user trust
- Expand dataset across different units and time frames
- Build a dashboard for real-time monitoring

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy, Scikit-learn
- Statsmodels (for SARIMA)
- Matplotlib, Seab
