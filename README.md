# 🌍 GeoData LATAM: Countries, States and Cities in South America

This project presents a structured dataset and visualization of countries, provinces (states), and localities (cities) across six South American countries using data sourced from the [countries-states-cities database](https://github.com/dr5hn/countries-states-cities-database).

## 📦 Dataset Overview

This project focuses on the following countries:

- 🇧🇷 **Brazil**
- 🇵🇾 **Paraguay**
- 🇺🇾 **Uruguay**
- 🇧🇴 **Bolivia**
- 🇨🇱 **Chile**
- 🇵🇪 **Peru**

### Tables

- `country`: country list with ISO codes and names
- `province`: administrative divisions (states/departments/regions)
- `locality`: cities and localities linked to each province

## 📊 Visual Analysis

A Jupyter Notebook is included for exploring and visualizing the dataset:
- Number of provinces per country
- Number of localities per country
- Top 10 provinces with the most localities

![preview](https://raw.githubusercontent.com/LucasNF84/geodatos-latam/main/assets/preview.png)

## 🛠️ Technologies Used

- Python 🐍
- Pandas 📊
- Matplotlib & Seaborn 📈
- Jupyter Notebook 📒
- SQL Server for structured storage 🗄️

## 📁 File Structure

```
📦 geodatos-latam/
├── countries.csv
├── states.csv
├── cities.csv
├── analisis_paises_provincias_localidades.ipynb
├── cargar_csv_sqlserver.py
└── README.md
```

## 🧠 Use Cases

- Geographic databases
- Regional data validation
- GIS visualizations
- Educational tools

## 🚀 Getting Started

Install dependencies:
```bash
pip install pandas matplotlib seaborn pyodbc
```

Run the notebook or the SQL loader script to visualize or populate your database.

## 📜 License

MIT License © [LucasNF84](https://github.com/LucasNF84)
