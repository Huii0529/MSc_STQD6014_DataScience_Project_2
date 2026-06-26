# MSc_STQD6014_DataScience_Project_2

# 📊 An Analysis of Credit Card Ownership Trends by Gender Across Countries (2011–2022)

## Project Overview

This project analyses global credit card ownership trends by gender using data from the World Bank Data360 database. The study explores differences in credit card ownership between males and females, examines ownership trends over time, compares ownership levels across countries, and investigates the overall distribution of credit card ownership worldwide.

The analysis was conducted entirely in **Python** using **Google Colab**, with data cleaning, transformation, visualization, and interpretation performed through popular data science libraries.

---

## Objectives

The objectives of this study are to:

- Analyse the trend of global credit card ownership from 2011 to 2022.
- Compare credit card ownership between males and females.
- Identify countries with the highest credit card ownership rates.
- Examine the global distribution of credit card ownership.
- Provide insights into financial inclusion and gender disparities in access to formal financial services.

---

## Dataset

**Source**

World Bank Data360

Indicator:
**Credit Card Ownership (% Age 15+)**

Dataset:
https://data360.worldbank.org/en/indicator/WB_GS_FIN7_T_A

---

## Technologies Used

- Python 3
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Data Preprocessing

The following preprocessing steps were performed:

- Uploaded the dataset into Google Colab
- Cleaned column names
- Renamed variables for easier interpretation
- Converted the dataset from wide format to long format using `pandas.melt()`
- Converted year values into numeric format
- Removed missing values from ownership percentages

Final dataset:

| Feature | Description |
|----------|-------------|
| Country | Country name |
| Sex | Male, Female, or Total |
| Year | Survey year |
| Ownership_Percentage | Percentage of adults (15+) owning a credit card |

---

## Exploratory Data Analysis

The project includes six visualisations:

1. **Credit Card Ownership Trend by Gender**
   - Compares male and female ownership trends over time.

2. **Overall Credit Card Ownership Trend**
   - Shows the average ownership trend for the total population.

3. **Top 10 Countries by Credit Card Ownership (2021)**
   - Identifies countries with the highest ownership percentages.

4. **Distribution of Ownership by Gender (Box Plot)**
   - Examines ownership variation and outliers across genders.

5. **Distribution of Credit Card Ownership (Histogram)**
   - Illustrates how ownership percentages are distributed among countries.

6. **Average Credit Card Ownership by Gender (Pie Chart)**
   - Compares the overall ownership share between males and females.

---

## Key Findings

- Global credit card ownership generally increased from 2011 to 2021.
- A decline in 2022 is observed, likely due to incomplete data availability.
- Male ownership is consistently higher than female ownership.
- Canada, Israel, and Iceland recorded the highest ownership rates in 2021.
- Most countries have relatively low credit card ownership, while only a few developed economies show very high adoption.
- Country-level differences are more pronounced than gender differences, suggesting that economic development and financial infrastructure play important roles in credit card adoption.

---

## Project Structure

```
├── CreditCardOwnershipAnalysis.ipynb
├── README.md
├── data/
│   └── credit_card_ownership.csv
├── images/
│   ├── gender_trend.png
│   ├── overall_trend.png
│   ├── top10_countries.png
│   ├── boxplot_gender.png
│   ├── histogram_distribution.png
│   └── gender_piechart.png
```

---

## How to Run

1. Open the notebook in **Google Colab**.
2. Upload the downloaded CSV dataset.
3. Install required libraries if necessary.
4. Run all notebook cells sequentially.
5. View the generated visualisations and analysis.

---

## Future Improvements

Potential extensions of this project include:

- Incorporating socioeconomic variables such as GDP per capita, income level, education, and employment.
- Performing statistical hypothesis testing (e.g., independent samples *t*-test).
- Building regression or machine learning models to predict credit card ownership.
- Comparing ownership patterns by region or income group.

---

## References

Antonijević, M. S., Ljumović, I., & Ivanović, Đ. (2022). *Is there a gender gap in financial inclusion across countries?* Journal of Women's Entrepreneurship and Education, 1–2, 79–96.

OECD. (2021). *Development Co-operation Report 2021: Shaping a Just Digital Transformation*. OECD Publishing.

OECD. (2025). *Supporting Informed and Safe Use of Digital Payments Through Digital Financial Literacy*. OECD Publishing.

---

## Author

**FANG JIA HUI**
MSc of Data Science & Analytics
Universiti Kebangsaan Malaysia (UKM)
