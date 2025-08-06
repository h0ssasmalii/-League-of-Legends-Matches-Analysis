# 🎮 League of Legends Data Analysis Project

## 📖 Overview
This project analyzes **League of Legends** match data to uncover key gameplay insights.  
The workflow covers **data cleaning, exploratory analysis, and interactive dashboard creation** to visualize performance trends and metrics.  

The dataset was downloaded from **Kaggle**, and **ChatGPT** was used as a coding assistant to help with some Python-related tasks.

---

## 🔍 Project Workflow

1. **Data Collection & Integration**
   - Downloaded raw match data from **Kaggle**.
   - Gathered multiple CSV files containing match statistics.
   - Merged all datasets into a single consolidated file for analysis.

2. **Data Cleaning & Preprocessing (Python)**
   - Removed duplicate entries and irrelevant columns.
   - Handled missing values.
   - Standardized column names and data formats.
   - Used **ChatGPT** to assist with some Python code snippets.

3. **Exploratory Data Analysis (Python)**
   - Calculated aggregated statistics such as win rate, kills, deaths, and assists.
   - Identified trends and patterns using descriptive statistics and group analysis.

4. **Interactive Analysis (Excel)**
   - Imported the cleaned dataset into Excel.
   - Created multiple **Pivot Tables** to analyze metrics by different dimensions (e.g., team side, champion, game duration).
   - Linked Pivot Tables with **Slicers** for dynamic filtering.

5. **Dashboard Creation (Excel)**
   - Built an **interactive Excel dashboard** connected to Pivot Tables.
   - Designed it to update dynamically based on slicer selections.
   - Used it to visualize KPIs such as win rate, average kills/deaths/assists, and match distribution.

---

## 📊 Key Insights
From the analysis, several key findings were identified:  

1. **Champion Balance**:  
   - Certain champions have a significantly higher **win rate**, suggesting they may be overpowered and could require balancing adjustments (**nerfs**).  

2. **Top Kill Champions**:  
   - Identified the champions with the highest average **kills** per match.  

3. **Vision Control Impact**:  
   - Teams that place more **wards** on the map tend to have a higher win probability.  

4. **Team Side Advantage**:  
   - **Blue side** teams win more matches compared to **red side** teams.  

5. **Minion Kills Correlation**:  
   - Teams with higher total **minion kills (CS)** tend to have a greater chance of winning.  

6. **Gold Advantage**:  
   - Winning teams usually have a higher **total gold** compared to losing teams.  

7. **ADC Role Performance**:  
   - Champions in the **ADC role** often achieve the highest number of kills.  

---

## 🛠 Tools & Technologies
- **Python**: Pandas, NumPy (data cleaning & exploration)
- **Excel**: Pivot Tables, Slicers, Dashboard design
- **Jupyter Notebook**: For analysis and documentation
- **Kaggle**: Dataset source
- **ChatGPT**: Coding assistance

---

## 📂 Repository Structure
📁 League-of-Legends-Analysis
│── 📂 data # Raw and cleaned datasets
│── 📂 notebooks # Python Jupyter notebooks
│── 📂 excel_dashboard # Excel file with Pivot Tables and Dashboard
│── 📂 images # Screenshots of dashboard & insights
│── README.md # Project documentation


---

## 📌 How to Use
1. Download the repository.
2. Open the **Jupyter Notebook** to view the Python data cleaning & analysis steps.
3. Open the **Excel dashboard** and use slicers to explore different metrics and insights.

---

## 📜 License
This project is for **educational purposes only**.  
League of Legends is a trademark of Riot Games, Inc. This analysis is not affiliated with or endorsed by Riot Games.
