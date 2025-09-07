# 🚗 Car Price Prediction  

A machine learning project to predict the **selling price of used cars** based on multiple features (e.g., age, fuel type, transmission, kilometers driven, etc.).  
The project uses **Python, Pandas, Seaborn, Matplotlib, and scikit-learn** for data preprocessing, visualization, and model building.  

---

## 📌 Project Workflow  
1. **Data Preprocessing**  
   - Removed unnecessary columns (`Car_Name`).  
   - Created new feature `Age` from `Year`.  
   - Handled outliers and duplicates.  
   - One-hot encoding for categorical variables.  

2. **Exploratory Data Analysis (EDA)**  
   - Boxplots, histograms, scatter plots, and correlation heatmaps.  
   - Visual analysis of relationships between features and `Selling_Price`.  

3. **Modeling**  
   - Applied **Linear Regression** with data scaling.  
   - Used **K-Fold Cross Validation** to evaluate model stability.  

4. **Evaluation Metrics**  
   - MAE (Mean Absolute Error)  
   - MSE (Mean Squared Error)  
   - RMSE (Root Mean Squared Error)  
   - R² Score  

---

## 📊 Results  
| Metric    | Test Set | Cross-Validation Mean |
|-----------|----------|------------------------|
| MAE       | ~1.20    | ~1.15 ± 0.14          |
| MSE       | ~3.71    | ~3.13 ± 1.31          |
| RMSE      | ~1.93    | ~1.72 ± 0.38          |
| R² Score  | ~0.89    | ~0.86 ± 0.03          |

The model achieved a strong **R² ≈ 0.89**, showing good predictive performance.

---

## 📷 Visualizations  
Some of the key visualizations generated in the project:  

- Distribution of numerical features  
- Selling Price vs. numerical & categorical features  
- Outlier detection  
- Predicted vs. Actual prices  

*(Plots are saved in the `images/` folder.)*

---

## 🛠️ Tech Stack  
- **Python**  
- **NumPy, Pandas**  
- **Matplotlib, Seaborn**  
- **scikit-learn**  

---

## 📌 How to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/car-price-prediction.git
   cd car-price-prediction

Run the notebook or Python script to reproduce results.

📄 License
This project is licensed under the MIT License – free to use with attribution.






