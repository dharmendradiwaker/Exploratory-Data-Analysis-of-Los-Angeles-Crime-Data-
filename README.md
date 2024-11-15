# Exploratory Data Analysis of Los Angeles Crime Data 🚔📊

## Overview
This project involves performing exploratory data analysis (EDA) on a large dataset containing over 802,000+ crime records from Los Angeles. The dataset includes 28 columns, and the analysis focuses on understanding crime patterns, victim demographics, crime types, and more. The insights are visualized using various tools, including **Pandas**, **Seaborn**, **Plotly**, and **Geo Heatmap**.

## Key Findings 🔍
- Over **50% of crime victims** are aged between **21-40 years**. 👶👨‍🦱
- More than **50% of victims** are **male**. 🚹
- Over **20% of crimes** were committed using **deadly weapons**. 🔪🧨

## Dataset 📁
The dataset contains more than **802,000** records, each representing a unique crime. It includes 28 columns such as:
- **Crime Type** 🔐
- **Victim Demographics** 🧑‍🦳
- **Crime Location** 📍
- **Time of Crime** ⏰
- **Weapon Used** 🔫

## Requirements 📋
- Python (version 3.6 or higher recommended)
- Required Python libraries:
  - Pandas (for data manipulation) 📊
  - Seaborn (for data visualization) 🎨
  - Plotly (for interactive visualizations) 📉
  - GeoPandas (for geographical data visualizations) 🌍
  - Matplotlib (for additional plotting support) 🖼️

You can install these dependencies using pip:
```bash
pip install pandas seaborn plotly geopandas matplotlib
```

## Analysis and Visualizations 📊
- **Data Cleaning**: Missing values handled, and data was preprocessed for analysis.
- **Visualization Techniques**:
  - **Scatter Plots**: To understand correlations and trends.
  - **Pie Charts**: For visualizing categorical distributions, like the gender of victims.
  - **Geo Heatmap**: To visualize crime hotspots across Los Angeles on a map.
  - **Histograms**: To understand the distribution of victims' ages and crime types.

## Setup ⚙️
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your_username/exploratory-data-analysis-los-angeles-crime.git
   ```

2. Navigate to the project folder:
   ```bash
   cd exploratory-data-analysis-los-angeles-crime
   ```

3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Jupyter Notebook or Python script:
   ```bash
   jupyter notebook Crime_EDA.ipynb
   ```

## How to Use 🧑‍💻
1. Load the dataset from the provided CSV file in the `data/` folder.
2. Follow the notebook to perform EDA and visualize the results.
3. Explore the plots and heatmaps to gain insights into crime trends and victim demographics.

## Conclusion 📌
The analysis provides valuable insights into crime patterns in Los Angeles, especially concerning the age and gender of victims, weapon usage, and the geographic distribution of crimes. This project can help inform policy and improve crime prevention strategies.

## Contributors 🙋‍♂️
- @Dharmendradiwaker12

---
