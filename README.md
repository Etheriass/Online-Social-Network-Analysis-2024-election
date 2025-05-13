# Online Social Network Analysis — IL-7 2024 Elections

This project analyzes Illinois’s 7th Congressional District to understand the relationship between demographics and voting behavior. Using U.S. Census and election data at the precinct level, we predict:

- Voter turnout percentage  
- Democratic vote share in the 2024 elections

---

## Repository Structure


```
.
├── Raw Datasets/           # Original census and precinct-level vote datasets
├── Training Datasets/      # Cleaned and merged datasets for model input
├── data_cleaning.ipynb     # Data preprocessing and feature engineering
├── analysis.ipynb          # Correlation, visualization, and EDA
└── model.ipynb             # Linear Regression and Neural Network training
```

---

## 🛠️ Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, TensorFlow)
- Precinct-level data processing
- Linear Regression & Feedforward Neural Network
- GeoPandas for spatial visualizations

---

## 📊 Highlights

- Trained models on over 390 precincts from IL-7  
- Achieved <2% error in 2024 vote prediction with linear regression  
- Performed correlation heatmaps to identify key demographic factors  
- Visualized spatial distribution of vote share and poverty rate

---

## 📁 Data Sources

- [U.S. Census](https://www.census.gov/)
- [Redistricting Data Hub](https://redistrictingdatahub.org/)
- [Ballotpedia Election Results](https://ballotpedia.org)

