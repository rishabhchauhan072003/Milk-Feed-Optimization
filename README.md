# 🐄 Project Title: Optimizing Feed Strategy for Maximum Milk Output

## 🔍 Project Overview:
This project aimed to identify the most effective feed strategies for maximizing milk production across three key dairy regions in New Zealand (Waikato, Canterbury, Southland). Using a synthetic dataset that simulated real-world patterns, we built a predictive model based on climate conditions, feed type, and feed quantity.

## 📊 Dataset Highlights:
- Timeframe: Jan 2019 – Dec 2021 (36 months)
- Features: Region, Feed_Type, Feed_Quantity_kg, Rainfall, Temperature
- Target: Monthly Milk Production in Litres

## 🧠 Techniques Used:
- Exploratory Data Analysis (Seaborn, Matplotlib)
- Feature Engineering (interaction variables: Rainfall × Feed, Temp × Feed)
- Random Forest Regression
- Model Evaluation (RMSE, R² Score)

## ✅ Key Insights:
- **Feed type matters**: 'Meal' feed generally resulted in higher milk yields than 'Pasture' or 'Silage'.
- **Feed quantity has a positive relationship** with milk output, especially between 8–13 kg/day.
- **Temperature and rainfall** had a nonlinear effect on production, with moderate climates being more optimal.
- **Feature importance** revealed that `Feed_Quantity_kg`, `Feed_Type_Meal`, and `Temperature_C` were the top drivers of milk production.

## 📈 Model Performance:
- **RMSE:** ~3524 litres  
- **R² Score:** **0.68**
- The model explains 68% of the variance in milk production and provides a solid foundation for feed planning decisions.

## 🧪 Tools Used:
Python, Pandas, Seaborn, Scikit-learn (Random Forest)

## 💡 Conclusion:
This project demonstrates how data science can be used to optimize feeding strategies in the dairy industry by analyzing climate and feed input variables. A better understanding of these factors can support sustainable and profitable farm systems.
