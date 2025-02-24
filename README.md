# Global-cases-analysis
 Hey! in this we are analysing data of "Covid 19" and ,Making data clean 
 # Data Visualization Project

## 📌 Overview
This project is all about exploring and visualizing data to uncover meaningful insights. We take a dataset containing global case statistics and clean, transform, and visualize it to better understand trends and patterns.

## 📂 About the Dataset
The dataset includes information on:
- **Country/Region**: Name of the country.
- **Total Cases**: The number of reported cases.
- **Deaths**: Total deaths recorded.
- **Recovered**: Number of recovered cases.
- **Active**: Currently active cases.
- **WHO Region**: The WHO classification of each country.
- **Confirmed**: Officially confirmed cases.

## 🔍 What We Did
Here’s a breakdown of the tasks we tackled:
1️⃣ **Loaded and displayed the first few rows of the dataset.**  
2️⃣ **Set the dataset index and renamed it for clarity.**  
3️⃣ **Reformatted column names to remove spaces.**  
4️⃣ **Handled missing values by filling them with the column mean.**  
5️⃣ **Checked for duplicate country entries and removed them if necessary.**  
6️⃣ **Calculated statistics like mean, median, and standard deviation of total cases.**  
7️⃣ **Cleaned up the Deaths column by replacing string values with the column mean.**  
8️⃣ **Converted the Deaths column into the correct numeric data type.**  
9️⃣ **Calculated total deaths and recoveries worldwide.**  
🔟 **Identified countries with more than 1 million cases.**  
1️⃣1️⃣ **Found countries where the recovery rate is above 95%.**  
1️⃣2️⃣ **Dropped unnecessary columns (WHO Region and Confirmed).**  
1️⃣3️⃣ **Identified the country with the most deaths.**  
1️⃣4️⃣ **Sorted countries by total deaths in descending order.**  
1️⃣5️⃣ **Created a new column `Total_Cases` by summing Deaths, Recovered, and Active.**  
1️⃣6️⃣ **Calculated the Death Rate and stored it in a new column.**  
1️⃣7️⃣ **Looked for countries where cases are rising but death rates remain low.**  
1️⃣8️⃣ **Displayed only the Country/Region and Death Rate columns.**  
1️⃣9️⃣ **Created a scatter plot to compare Total Cases and Deaths.**  
2️⃣0️⃣ **Saved the cleaned dataset as a CSV file.**  

## 🚀 How to Run This Project
### **What You’ll Need:**
- Python 3.x
- Pandas
- Matplotlib
- Seaborn

### **Steps to Run:**
1. Install the required libraries:
   ```sh
   pip install pandas matplotlib seaborn
   ```
2. Make sure the dataset is in the project directory.
3. Open the Jupyter Notebook (`.ipynb`) and run the cells to see the analysis and visualizations.

## 📊 What We Discovered
- The dataset was cleaned to remove missing values and duplicates.
- We calculated key statistics for total cases, deaths, and recoveries.
- We identified countries with high recovery rates and low death rates.
- A **scatter plot** was created to visualize the relationship between Total Cases and Deaths.
- The cleaned dataset was saved as a **CSV file** for further analysis.

## 📌 What’s Next?
- Adding **interactive visualizations** for better data exploration.
- Using **machine learning models** to predict trends.
- Building a **dashboard** for real-time tracking.

---

### ✨ Created for Data Science & Visualization Enthusiasts 🚀


