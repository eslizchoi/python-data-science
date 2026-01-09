# Car Price Analysis using ANOVA

## 📌 Problem Statement
Our friend Otis wants to sell his car but is unsure about the right price.
This project aims to identify the factors that significantly affect car prices, helping sellers maximize profit while offering reasonable prices to buyers.

## 📊 Dataset
- Automobile dataset
- Target variable: price
- Key features: manufacturer (make), body-style, drive-wheels, engine-size

## 🧹 Data Cleaning & Preprocessing
- Handled missing values represented as "?"
- Converted variables to appropriate data types
- Created price bins for categorical analysis
- Applied one-hot encoding to categorical variables

## 🔍 Exploratory Data Analysis (EDA)
- Distribution of car prices
- Boxplots comparing prices across manufacturers
- Heatmaps for feature relationships

## 📐 Statistical Analysis
- One-way ANOVA to test price differences between manufacturers
- Example comparison: Honda vs Subaru
- Interpretation based on F-statistic and p-value

## 📈 Key Findings
- Car prices vary significantly across manufacturers
- Manufacturer is a statistically significant factor affecting price
- Certain body styles and drive-wheel types are associated with higher prices

## 🛠 Tools & Libraries
- Python
- pandas, numpy
- matplotlib, seaborn
- scipy.stats

## 📂 Project Structure
