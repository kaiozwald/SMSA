# 🌍 World Happiness Report – Exploratory Data Analysis (EDA)

This project presents an exploratory data analysis (EDA) of the World Happiness Report dataset, aiming to uncover key patterns and relationships that influence happiness scores across different countries and years.

---

## 📊 Project Objective

The main goal is to understand the distribution, correlation, and insights of the happiness score and its contributing factors (economy, health, freedom, etc.) through:

- Data cleaning and merging multiple yearly datasets into one consistent format.
- Visualization and statistical exploration using Python and Power BI.
- Identifying trends and relationships that drive happiness across countries.

---

## 🧠 Tools & Technologies

- **Python**: Pandas, Matplotlib, Seaborn
- **Power BI**: Interactive dashboards for country/year analysis
- **Jupyter Notebook**: For step-by-step EDA and visualization
- **Git & GitHub**: Version control and project hosting

---

## 📁 Dataset Description

Each record in the dataset includes:

- `Country`
- `Year`
- `Rank`
- `Score`
- `Economy`
- `Family`
- `Health`
- `Freedom`
- `Trust`
- `Generosity`
- `Dystopia Residual`

---

## 🔍 Key Analysis Steps

### 1. Data Cleaning
- Removed inconsistent or duplicate columns across years
- Unified data into a single clean DataFrame
- Checked for and confirmed absence of missing values

### 2. Univariate Analysis
- Distribution plots for each feature
- Identified skewness and normality in features like Score, Economy, Trust, etc.

### 3. Correlation Analysis
- Heatmap and pair plot to show feature relationships
- Strong correlation found between Score and Economy, Health, Family

### 4. Insights Exploration
- Scatter plots between Score and Economy, annotated by Country
- Identified top and bottom 10 countries by Score
- Found possible areas for normalization due to skewed distributions

### 5. Power BI Dashboard
- **Global**: Average scores by year, most/least ranked countries, top 10, bottom 10, and score-economy relation
- **Country**: Line chart and table for a selected country across all years

---

## 🔎 Key Insights

- Countries with high economy, health, and family support tend to score higher in happiness.
- Trust and generosity are often low and right-skewed, but still positively contribute.
- The Score distribution is nearly normal, while other features are often right-skewed.
- Top 10 countries remain consistent with Nordic countries leading most years.
- Bottom 10 countries show consistently low scores with poor economic and health indicators.


## Project Images
![Global View](https://github.com/kaiozwald/SMSA/blob/main/Global.png)
![alt text](https://github.com/kaiozwald/SMSA/blob/main/Country.png)
