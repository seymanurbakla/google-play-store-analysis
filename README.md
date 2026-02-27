# Google Play Store Apps Analysis and Interactive Dashboard

This project analyzes the Google Play Store market using a dataset containing more than 10,000 mobile applications. The main objective is to examine relationships between app pricing, user ratings, installation numbers, and category distribution, and to present these findings through an interactive dashboard.

---

## Project Overview

### Data Cleaning
The raw dataset was prepared before analysis by performing several preprocessing steps:
- Handling missing values
- Removing duplicate records
- Converting the **Size**, **Installs**, and **Price** columns into appropriate numeric formats

### Exploratory Data Analysis (EDA)
Exploratory analysis was conducted to better understand general market trends:
- Distribution of application ratings was analyzed
- Category-based comparisons were performed
- The **Family** and **Game** categories were identified as the most populated categories in the dataset

### Pricing Analysis
The relationship between application type and user satisfaction was examined:
- Free and paid applications were compared
- Paid applications were observed to have more stable ratings and a slightly higher median rating value

### Text Analysis
A basic text mining process was applied to application titles:
- Frequently used words were extracted
- A WordCloud visualization was created to identify commonly used keywords in popular applications

### Interactive Dashboard
An interactive web-based dashboard was developed using Plotly Dash:
- Users can filter applications by category
- Visualizations update dynamically based on user selection

---

## Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn, Plotly  
- Plotly Dash  
- WordCloud  
- Git and GitHub  

---

## Key Findings

- A positive relationship exists between the number of **Reviews** and total **Installs**, suggesting that user engagement increases application visibility.
- Free applications show higher variation in ratings, while paid applications tend to maintain more consistent scores.
- Words such as *Free*, *Game*, and *Cleaner* appear frequently in application titles, indicating common naming and optimization strategies.

---

## Project Structure
