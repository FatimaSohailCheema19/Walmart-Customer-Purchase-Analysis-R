# 🛒 Walmart Customer Purchase Analysis in R

An exploratory data analysis and visualization project focused on understanding **Walmart customer purchasing behavior** using **R, ggplot2, dplyr, and tidyverse**.

The project analyzes customer demographics, product sales, city-wise behavior, purchase trends, and spending patterns to generate practical business insights from retail data.

---

## 📌 Project Overview

Retail businesses generate large amounts of customer and transaction data.

This project explores Walmart customer purchase data to understand:

- Who the most active customers are
- Which products generate higher sales
- How purchasing behavior differs by age and gender
- Which cities show greater customer activity
- How sales change over time
- Which days experience higher shopping activity

The analysis combines descriptive statistics with multiple visualizations to better understand customer behavior and purchasing trends.

---

## 🎯 Objectives

The main objectives of this project were to:

- Understand the structure of the Walmart customer dataset
- Check the dataset for missing values
- Analyze customer demographics
- Explore age and gender distributions
- Compare customer activity across cities
- Calculate sales by product
- Analyze sales trends over time
- Identify peak shopping days
- Compare spending patterns across demographic groups
- Generate practical recommendations from the analysis

---

## 🛠️ Technologies Used

- R
- R Markdown
- ggplot2
- tidyverse
- dplyr
- lubridate
- Data Visualization
- Exploratory Data Analysis

---

## 📊 Dataset

The dataset contains information about Walmart customer shopping behavior.

It includes information related to:

- Customer demographics
- Age
- Gender
- City
- Product information
- Purchase amounts
- Purchase dates
- Transaction records

The dataset is used to study customer preferences, sales behavior, demographic patterns, and purchasing trends.

The original dataset is not included in this repository.

---

## 🔍 Dataset Exploration

The first stage of the analysis examines the structure of the dataset using functions such as:

- `str()`
- `head()`
- `summary()`

Missing values are also checked across all columns.

The analysis found that the dataset did not require extensive missing-value preprocessing before visualization.

---

## 👥 Customer Demographic Analysis

### Age Distribution

Customer activity was analyzed across different age groups.

The visualization indicates that customers in the **26–45 age range** represent one of the most active customer groups in the dataset.

This suggests that this age group may be particularly important for targeted marketing campaigns.

---

### Gender Distribution

Customer participation was also compared by gender.

The analysis indicates that male customers show slightly higher purchasing activity in the dataset.

Gender-based analysis can help identify differences in customer participation and spending behavior.

---

## 🌆 City-Wise Customer Activity

Customer activity was compared across cities using a bar chart.

The analysis showed differences in customer participation between locations, with some cities contributing more customers than others.

This type of analysis can support:

- Location-based marketing
- Regional sales planning
- City-specific promotions
- Inventory decisions

---

## 💰 Product Sales Analysis

Total sales were calculated for individual products using purchase amounts.

Products were grouped and their total sales values were calculated before visualization.

This analysis helps identify:

- High-performing products
- Lower-performing products
- Important revenue contributors
- Product areas that may deserve additional promotion

---

## 📈 Sales Over Time

Purchase dates were converted into date format and used to analyze daily sales.

A time-series visualization was created to observe how total sales changed across different dates.

The results show that sales fluctuate over time, with identifiable periods of higher and lower purchasing activity.

Understanding these patterns can help businesses plan:

- Promotions
- Inventory
- Staffing
- Marketing campaigns

---

## 📅 Peak Shopping Days

The day of the week was extracted from each purchase date.

Purchases were then visualized by weekday to identify differences in shopping activity.

Certain days showed higher purchase activity than others, helping identify possible peak shopping periods.

---

## 🧠 Advanced Customer Insights

### Purchase Amount by Age Group

A boxplot was used to compare purchase amounts across different age groups.

The analysis suggests that middle-aged customers generally demonstrate stronger purchasing behavior.

This can help businesses identify valuable demographic groups.

---

### Purchase Behavior by Gender

Purchase amounts were also compared between genders.

The analysis showed slightly higher spending patterns among male customers in the dataset.

---

### Purchase Amount by City

Customer spending was compared across cities using boxplots.

The results show that purchasing behavior differs by location, with customers in some cities spending more per transaction than customers in others.

This insight can support geographically targeted business strategies.

---

## 📊 Key Findings

The main findings from the analysis include:

- Customers aged **26–45** are among the most active buyers
- Some products generate significantly higher sales than others
- Purchasing activity changes across different dates
- Certain days experience greater shopping activity
- Male customers show slightly higher spending patterns
- Customer spending differs across cities

---

## 💼 Business Recommendations

Based on the exploratory analysis, the following recommendations can be considered:

### 🎯 Target High-Activity Age Groups

Marketing campaigns can focus more strongly on customer groups showing higher purchasing activity.

---

### 🛍️ Promote High-Performing Products

Products generating stronger sales can receive greater promotional attention and inventory support.

---

### 📅 Plan Around Peak Shopping Periods

Retail campaigns and offers can be scheduled around periods and days with greater purchase activity.

---

### 🌍 Use Location-Based Strategies

Cities with stronger customer activity or higher spending can receive customized promotional campaigns.

---

### 📦 Improve Inventory Planning

Understanding product demand and purchase timing can help improve stock planning and reduce shortages during high-demand periods.

---

## 📁 Repository Structure

Walmart-Customer-Purchase-Analysis-R/

├── analysis/

│   └── walmart_customer_analysis.Rmd

│

├── report/

│   └── Walmart_Customer_Purchase_Analysis.pdf

│

└── README.md

---

## 📄 R Markdown Analysis

The complete source analysis is available in:

**analysis/walmart_customer_analysis.Rmd**

The R Markdown file contains:

- Dataset loading
- Dataset inspection
- Missing-value analysis
- Age distribution
- Gender distribution
- City-wise analysis
- Product sales analysis
- Daily sales trends
- Peak shopping day analysis
- Age-based purchase comparison
- Gender-based purchase comparison
- City-based spending analysis
- Business insights
- Recommendations

---

## 📑 Project Report

The rendered project report is available in:

**report/Walmart_Customer_Purchase_Analysis.pdf**

It presents the analysis and visualizations generated from the R Markdown implementation.

---

## 📦 Required R Libraries

The analysis uses the following R libraries:

- tidyverse
- ggplot2
- lubridate

These libraries can be installed in R using:

**install.packages(c("tidyverse", "ggplot2", "lubridate"))**

---

## ▶️ How to Run

1. Clone or download this repository.
2. Open `walmart_customer_analysis.Rmd` in RStudio.
3. Download or place the required Walmart dataset in the working directory.
4. Ensure that the dataset filename or path matches the path used in the R Markdown file.
5. Install the required R packages.
6. Run the code chunks individually or knit the complete R Markdown document.

---

## 📉 Analysis Workflow

The project follows the general workflow:

**Dataset Loading → Data Understanding → Missing Value Check → Demographic Analysis → Product Analysis → Time-Based Analysis → Advanced Visualizations → Business Insights**

---

## 🧠 Key Learning Outcomes

Through this project, I practiced:

- Exploratory Data Analysis in R
- Data manipulation using dplyr
- Data visualization using ggplot2
- Working with dates using lubridate
- Grouping and summarizing data
- Creating bar charts
- Creating line charts
- Creating boxplots
- Retail customer analysis
- Business interpretation of visualizations

---

## 🚀 Possible Future Improvements

This project can be extended further through:

- Customer segmentation
- Predictive sales modeling
- Product recommendation systems
- Customer lifetime value analysis
- Interactive dashboards using Shiny
- More advanced time-series analysis
- Geographic sales visualization
- Product-level profitability analysis
- Customer clustering
- Forecasting future sales

---

## 🎓 Academic Context

This project was developed as part of a **Data Visualization Lab assignment**.

The purpose of the assignment was to apply R-based data visualization techniques to a retail dataset and generate meaningful insights from customer and purchase information.

---

## 👩‍💻 Author

**Fatima Sohail**

BS Data Science  
GIFT University

---

## ⭐ Support

If you find this project useful for learning R, exploratory data analysis, or data visualization, consider giving the repository a ⭐.
