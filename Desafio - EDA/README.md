# 🚀 Applied Machine Learning - Rocketseat Course

This repository contains practical projects and challenges from the **Rocketseat Machine Learning & Artificial Intelligence** course. Each project demonstrates real-world applications of data science and machine learning techniques.

---

## 📚 About This Repository

This repository is organized by challenges and projects that cover various aspects of Machine Learning, from Exploratory Data Analysis (EDA) to model building and deployment.

---

## 🎯 Challenge 1: Exploratory Data Analysis (EDA) - Netflix Daily Top 10

### Overview

This project performs a comprehensive **Exploratory Data Analysis (EDA)** on the Netflix Daily Top 10 dataset. The analysis focuses on understanding data structure, identifying missing values, detecting outliers, and extracting meaningful insights from the streaming platform's top-performing content.

### Dataset

- **Dataset**: Netflix Daily Top 10
- **Records**: 7,100 entries
- **Columns**: 10 features
- **Period**: April 1, 2020 to March 11, 2022

### Key Features Analyzed

- **Rank**: Daily ranking position
- **Year to Date Rank**: Cumulative ranking for the year
- **Last Week Rank**: Previous week's ranking
- **Title**: Content title
- **Type**: Content type (Movie/TV Show)
- **Netflix Exclusive**: Whether content is Netflix exclusive
- **Netflix Release Date**: Original release date on Netflix
- **Days In Top 10**: Number of days content stayed in Top 10
- **Viewership Score**: Accumulated viewership score

### Analysis Performed

1. **Data Structure Inspection**
   - Dataset dimensions and column types
   - Data type identification and conversion

2. **Missing Values Analysis**
   - Identification of null values
   - Heatmap visualization of missing data distribution
   - Data cleaning (filling missing values in 'Netflix Exclusive')

3. **Temporal Analysis**
   - Date range identification
   - Feature engineering: 'Age at Top 10' calculation

4. **Outlier Detection**
   - Statistical summary using `describe()`
   - Boxplot visualizations for:
     - Days In Top 10 by content type
     - Viewership Score by content type
   - Identification of extreme outliers

### Key Insights

- The dataset contains **2,501 missing values** in the 'Netflix Exclusive' column
- Analysis period spans **nearly 2 years** of Netflix Top 10 data
- Outliers identified in both 'Days In Top 10' and 'Viewership Score' metrics
- Content type distribution reveals interesting patterns in performance metrics

### Visualizations

- Missing values heatmap
- Boxplots for outlier detection (Days In Top 10 and Viewership Score)

---

## 🛠️ Technologies Used

- **Python** 🐍
- **Pandas** 📊 - Data manipulation and analysis
- **Matplotlib** 📈 - Data visualization
- **Seaborn** 🎨 - Statistical data visualization
- **Jupyter Notebook** 📓 - Interactive development environment
- **NumPy** 🔢 - Numerical computing (via Pandas)

---

## 📁 Project Structure

```
Desafio - EDA/
├── desafio-eda.ipynb          # Main analysis notebook
├── netflix_daily_top_10.csv    # Dataset
├── null_heatmap.png            # Missing values visualization
├── days_in_top10_outliers.png # Outliers visualization (Days)
├── score_outliers.png          # Outliers visualization (Score)
└── README.md                   # This file
```

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab
- Required Python packages (install via pip):

```bash
pip install pandas matplotlib seaborn jupyter
```

### Running the Analysis

1. Clone this repository:
```bash
git clone https://github.com/mmancilha/Applied-ML.git
cd Applied-ML/Desafio\ -\ EDA
```

2. Open the Jupyter Notebook:
```bash
jupyter notebook desafio-eda.ipynb
```

3. Run all cells to execute the complete analysis

---

## 📊 Results

The analysis provides insights into:
- Data quality and completeness
- Content performance patterns
- Outlier identification for further investigation
- Feature engineering opportunities for machine learning models

---

## 🔮 Future Challenges

This repository will be updated with additional challenges from the Rocketseat ML & AI course, including:

- [ ] Feature Engineering
- [ ] Model Training and Evaluation
- [ ] Model Deployment
- [ ] Advanced ML Techniques
- [ ] And more...

---

## 📝 License

This project is part of the Rocketseat Machine Learning & Artificial Intelligence course.

---

## 👤 Author

**Marcelo Mancilha**

- GitHub: [@mmancilha](https://github.com/mmancilha)

---

## 🙏 Acknowledgments

- **Rocketseat** for providing excellent ML & AI course content
- Netflix for making the dataset available for educational purposes

---

<div align="center">

**Made with ❤️ as part of the Rocketseat ML & AI Course**

</div>

