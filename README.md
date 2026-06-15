# ✈️ Air Calamities Analysis (1919–2023)

Exploratory analysis of aviation accidents worldwide, spanning over a century of flight history.

---

## 📌 Project Overview

This project analyzes a dataset of aviation accidents from **1919 to 2023**, covering commercial, military, and private flights. The goal is to uncover patterns and trends in air calamities through data cleaning, feature engineering, and data visualization.

---

## 📊 Key Questions Explored

1. **Which nations had the most aviation accidents?**
2. **Which days of the week are most accident-prone?**
3. **Which are the safest major commercial airlines?**
4. **Which aircraft types caused the most fatalities?**
5. **What changed after 9/11?** — trends in accidents and fatalities
6. **In which seasons do accidents peak?**
7. **Has average mortality improved over time?**
8. **How are accidents distributed by category** (accidental, criminal, fire, unknown...)?
9. **World map of accidents by country** (interactive choropleth)

---

## 🛠️ Technologies Used

| Tool | Purpose |
|------|---------|
| Python 3 | Core programming language |
| Pandas | Data cleaning and manipulation |
| NumPy | Numerical operations |
| Matplotlib | Static data visualizations |
| Plotly Express | Interactive world map (choropleth) |
| Jupyter Notebook | Development environment |

---

## 📁 Project Structure

```
air-calamities-analysis/
│
├── Air_calamities_analysis_from_1919_to_2023.ipynb   # Main notebook
├── aviation-accidents.csv                             # Source dataset
└── README.md
```

---


## 📈 Highlights

- **USA** leads in total aviation accidents by a significant margin
- Accidents and fatalities show a **clear downward trend after 9/11**, driven by stricter international regulations
- **Aeroflot** historically shows the highest average fatalities per accident among major airlines
- The **Douglas DC-3** and **Boeing 737** dominate total fatality counts due to their widespread historical use
- **December and January** show slight seasonal peaks in accident frequency

---

## 📂 Dataset

The dataset `aviation-accidents.csv` contains records with the following key fields:

| Column | Description |
|--------|-------------|
| `date` | Date of the accident |
| `year` | Year of the accident |
| `country` | Country where it occurred |
| `operator` | Airline or operator |
| `type` | Aircraft type |
| `fatalities` | Number of fatalities |
| `cat` | Accident category code |

> Dataset sourced from public aviation safety databases.

---

## 👤 Author

**Matteo Daviddi**  
Data Analyst  
[LinkedIn](https://www.linkedin.com/in/matteodaviddi) · [GitHub](https://github.com/matteodaviddi)

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).
