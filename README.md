# ShellxEdunet_internship
# 🌍 Prediction of CO₂ Emissions from Country-Specific Data

This project analyzes country-specific indicators and applies machine learning to predict **CO₂ emissions** using the **World Bank Climate Change Dataset**.

## 📌 Project Goals

- Understand the relationship between greenhouse gas emissions and various socioeconomic, environmental, and population indicators.
- Develop predictive models for **CO₂ emissions**.
- Identify key drivers of CO₂ emissions across countries and over time.

---

## 📁 Dataset

**Source**: [World Bank Climate Change Data](https://datacatalog.worldbank.org/search/dataset/0037712)

### Key Features:

- `country`: Name of the country
- `year`: Time range (1990–2011)
- `CO₂ emissions`: Total and per capita
- `Population`: Total, urban population, growth %
- `Economy`: GDP, GNI, FDI
- `Agriculture`: Cereal yield, land use
- `Energy`: Energy consumption per capita, per GDP
- `Climate`: National disasters, protected land areas
- `Health`: Medical personnel counts, mortality rates

---

## 🛠️ Project Structure

```bash
├── data/
│   └── climate_change_download_0.xls   # Original dataset
├── cleaned/
│   └── data_cleaned1.csv                # Final cleaned dataset
├── notebooks/
│   └── week1.ipynb # Preprocessing steps
├── README.md

