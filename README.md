# Titanic-Survival-Analysis
Exploratory Data Analysis of Titanic dataset using Python, Pandas, and Data Visualization to identify survival factors

# 🚢 Titanic Survival Analysis

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-1.3+-green.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4+-orange.svg)
![Status](https://img.shields.io/badge/Status-Complete-success.svg)

## 📊 Project Overview

An in-depth Exploratory Data Analysis (EDA) of the Titanic disaster dataset to identify key factors that influenced passenger survival rates. This project demonstrates data cleaning, statistical analysis, and data visualization skills essential for data analyst roles.

## 🎯 Objectives

- Analyze survival rates across different passenger demographics
- Identify correlations between passenger attributes and survival
- Create compelling visualizations to communicate insights
- Apply statistical thinking to historical disaster data

## 🔍 Key Findings

### 1. Gender as Primary Survival Factor
- **Female survival rate: 74.2%** vs **Male: 18.9%**
- "Women and children first" policy was clearly enforced
- Gender alone increased survival chances by **4x**

### 2. Socioeconomic Class Impact
- **1st Class: 63%** survival rate
- **2nd Class: 47%** survival rate
- **3rd Class: 24%** survival rate
- Higher class passengers had **2.6x better survival odds**

### 3. Age Distribution
- Average survivor age: **28.3 years**
- Average non-survivor age: **30.0 years**
- Minimal age impact overall, but children prioritized within groups

### 4. Overall Statistics
- **Only 38.4% survived** (342 out of 891 passengers)
- **549 fatalities** in total
- Clear evidence of social inequality in disaster response

## 🛠️ Technologies Used

- **Python 3.8+**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical visualizations
- **Jupyter Notebook** - Interactive development

## 📁 Project Structure
```
Titanic-Survival-Analysis/
│
├── Titanic_EDA.ipynb          # Main analysis notebook
├── README.md                   # Project documentation
└── data/                       # Dataset folder (if applicable)
```

## 📈 Visualizations

The project includes multiple visualization types:

- **Bar Charts** - Comparing survival rates across categories
- **Pie Charts** - Overall survival distribution
- **Histograms** - Age distribution analysis
- **Multi-panel Dashboard** - Comprehensive overview


## 🔢 Data Analysis Process

1. **Data Loading & Exploration**
   - Loaded 891 passenger records
   - Examined 12 features including demographics and ticket information

2. **Data Cleaning**
   - Handled 177 missing Age values (filled with median)
   - Removed Cabin column (77% missing data)
   - Imputed 2 missing Embarkation values

3. **Exploratory Analysis**
   - Calculated survival rates by gender, class, age
   - Identified correlations between features
   - Statistical significance testing

4. **Visualization & Storytelling**
   - Created 5+ different chart types
   - Built comprehensive dashboard view
   - Communicated actionable insights

## 💡 Skills Demonstrated

✅ **Data Cleaning** - Handling missing values, data type conversions  
✅ **Data Analysis** - Grouping, aggregation, statistical calculations  
✅ **Data Visualization** - Creating clear, informative charts  
✅ **Statistical Thinking** - Identifying patterns and correlations  
✅ **Communication** - Translating data into business insights  
✅ **Python Programming** - Pandas, NumPy, Matplotlib, Seaborn  

## 🚀 How to Run This Project

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Running the Analysis
1. Clone this repository:
```bash
git clone https://github.com/[YOUR_USERNAME]/Titanic-Survival-Analysis.git
```

2. Navigate to the project directory:
```bash
cd Titanic-Survival-Analysis
```

3. Open Jupyter Notebook:
```bash
jupyter notebook Titanic_EDA.ipynb
```

4. Run all cells to see the analysis

## 📊 Dataset Information

- **Source:** Kaggle Titanic Dataset
- **Rows:** 891 passengers
- **Columns:** 12 features
- **Target Variable:** Survived (0 = No, 1 = Yes)

### Features:
- PassengerId, Survived, Pclass (Ticket Class)
- Name, Sex, Age
- SibSp (Siblings/Spouses), Parch (Parents/Children)
- Ticket, Fare, Cabin, Embarked (Port)

## 🎓 Learnings & Takeaways

- Understanding the importance of data quality and cleaning
- How social factors influenced disaster outcomes
- Effective visualization techniques for different data types
- Statistical analysis for real-world datasets
- Importance of storytelling in data analysis

## 🔮 Future Enhancements

- [ ] Implement predictive modeling (ML algorithms)
- [ ] Hypothesis testing (Chi-square, T-tests)
- [ ] Interactive dashboard using Plotly or Dash
- [ ] Comparison with other maritime disasters
- [ ] Time-series analysis of rescue operations

## 👤 Author

**Avinash Reddy Nalla**

- 🎓 B.Tech in Computer Science Engineering (2025)
- 📧 Email: avinashreddy600@gmail.com
- 💼 LinkedIn: www.linkedin.com/in/avinash-reddy-nalla-1786a4233
- 🐱 GitHub: https://github.com/Avinashreddy001

## 📝 License

This project is open source and available for educational purposes.

## 🙏 Acknowledgments

- Kaggle for providing the Titanic dataset
- The data science community for inspiration and learning resources

---

⭐ **If you found this project helpful, please consider giving it a star!** ⭐

*Last Updated: October 2025*
```
