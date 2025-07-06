# ShellxEdunet_internship
# 🌍 Prediction of CO₂ Emissions from Country-Specific Data

This project analyzes country-specific indicators and applies machine learning to predict **CO₂ emissions** using the **World Bank Climate Change Dataset**.

## 🚀 **Project Overview**

- **Goal:** Develop a predictive model that estimates carbon emissions to support climate policy and planning.  
- **Dataset Source:** [World Bank Climate Change Data](https://data.worldbank.org/topic/climate-change)  
- **Model Used:** Random Forest Regressor  
- **Tools & Technologies:** Python, pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels

---

## 📁 **Dataset**

**Key Features:**

- **country:** Name of the country  
- **year:** Time range (1990–2011)  
- **CO₂ emissions:** Total emissions, per capita emissions  
- **Population:** Total population, urban population, population growth %  
- **Economy:** GDP, GNI, FDI inflows  
- **Agriculture:** Cereal yield, land use statistics  
- **Energy:** Energy consumption per capita, energy use per GDP unit  
- **Climate:** Natural disasters data, % protected land areas  
- **Health:** Medical personnel counts, mortality rates

---

## 📂 **Project Structure**

\```
project_root/
├── data/
│   └── climate_change_download_0.xls      # Original dataset from World Bank
├── cleaned/
│   └── data_cleaned.csv                   # Final cleaned dataset after preparation
├── notebooks/
│   ├── 1_data_preparation.ipynb           # Data loading and cleaning
│   ├── 2_data_exploration.ipynb           # Data exploration and analysis
│   └── 3_model_building.ipynb             # Model training and evaluation
├── model/
│   └── carbon_emission_model.pkl          # Saved Random Forest model (download below)
├── README.md
\```


## 🔬 **Methodology**

1. **Data Preparation:** Loaded and cleaned the climate change dataset, handling missing values and verifying data types.  
2. **Data Exploration:** Analysed descriptive statistics, feature distributions, and correlations to identify key predictors.  
3. **Model Building:**  
   - Split data into training and testing sets  
   - Trained a Random Forest Regressor  
   - Evaluated performance using **R² score** and **Mean Squared Error (MSE)**

---

## 💾 **Model Output**

The trained model has been saved and is accessible here:

[🔗 **Download Model File**](https://drive.google.com/file/d/13qu7mvKIt8na3PWicEZ8uoMCX_9ufsU2/view?usp=share_link)

---

## 📈 **Results**

- **R² Score:** Indicates the proportion of variance in emissions explained by the model  
- **Mean Squared Error (MSE):** Measures average squared difference between predicted and actual values

*(See `3_model_building.ipynb` for detailed outputs)*

---

## 🏁 **Conclusion**

- Successfully built a **Random Forest regression model** to predict carbon emissions using climate and economic data.  
- Gained hands-on experience in the **end-to-end machine learning pipeline**.  
- Future work includes adding features like **energy source breakdown** and testing advanced models such as **Gradient Boosting** for improved accuracy.

---

## 👤 **Author**

**Ritam Santra**  
- **AICTE Student ID:** STU682afb63b59811747647331  
- **AICTE Internship ID:** INTERNSHIP_1746416864681834e0e35d8

---

✨ *Feel free to fork, use, or extend this project for your climate data science explore
