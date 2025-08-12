# Heart Disease Prediction

This project uses the **Heart Disease dataset from Kaggle** to predict the presence of heart disease using **Decision Tree** and **Random Forest** classifiers. It includes model training, overfitting analysis, feature importance interpretation, and evaluation with cross-validation.

## 📂 Dataset
- Source: [Kaggle Heart Disease Dataset](https://www.kaggle.com/ronitf/heart-disease-uci)
- Target Variable: `target` (0 = No Disease, 1 = Disease)

## ⚙️ Steps
1. **Data Understanding & Preprocessing**
   - Check missing values, data types, and summary statistics.
   - Encode categorical variables and scale features.

2. **Model Training**
   - Train a **Decision Tree Classifier** and visualize the tree.
   - Analyze overfitting and control tree depth.
   - Train a **Random Forest Classifier** for comparison.

3. **Feature Importance**
   - Identify the most influential features for prediction.

4. **Evaluation**
   - Compare accuracy between models.
   - Use **cross-validation** for performance stability.

## 📊 Results
| Model                  | Accuracy | CV Mean Accuracy |
|------------------------|----------|------------------|
| Decision Tree (depth=3)|  0.985%     | 0.83%             |
| Random Forest          | 0.9970%    |  0.9853%             |




