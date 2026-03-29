# 📊 Birth Data Analytics Dashboard

## 📌 Project Overview

The Birth Data Analytics Dashboard is an interactive Power BI project designed to analyze birth registration trends across districts, mandals, and panchayats. It provides insights into demographic patterns and helps stakeholders make data-driven decisions.

## 💼 Business Problem
Government authorities need insights into birth registration trends to identify regional gaps, improve planning, and allocate resources effectively.

## 🎯 Objectives

* Analyze birth registration trends across regions
* Understand gender distribution patterns
* Compare performance across districts and mandals
* Enable detailed data exploration using interactive features

## 🛠 Tools & Technologies

* Power BI
* SQL
* DAX
* Data Visualization

## 📂 Dataset

The dataset includes:

* District, Mandal, Panchayat
* Gender
* Birth Registration Count
* Date/Year

## 📈 Dashboard Features

* Donut, pie, waterfall, and bar charts
* Gender distribution analysis
* Regional comparison of birth registrations
* Interactive slicers and filters
* Drill-through analysis for detailed insights

  ## 📊 Sample DAX Measures

```DAX
Total Births = SUM(BirthData[Birth Count])

Gender Ratio = 
DIVIDE(
    CALCULATE(SUM(BirthData[Birth Count]), BirthData[Gender] = "Male"),
    CALCULATE(SUM(BirthData[Birth Count]), BirthData[Gender] = "Female")
)

## 📷 Dashboard Preview
![Overview](images/dashboard_overview.png)
![Gender Analysis](images/gender_analysis.png)

## 🔍 Key Insights
- Certain districts show higher birth registration rates.
- Gender distribution is relatively balanced across regions.
- Noticeable trends in registration frequency across time periods.
  
## 📁 Repository Structure
```
Birth-Data-Analytics-Dashboard
│
├── dashboard
│   └── Birth Data Analytics Dashboard.pbix
│
├── images
│   ├── dashboard_overview.png
│   ├── gender_analysis.png
│
└── README.md
## 🚀 How to Use

1. Download the `.pbix` file
2. Open in Power BI Desktop
3. Explore dashboards using filters and slicers

## 🔮 Future Enhancements

* Integration with live data sources
* Predictive analytics using machine learning
* Enhanced visualizations and KPIs

## 👤 Author
Meghana Reddy Komandla

🔗 GitHub: https://github.com/MeghanaKomandla
