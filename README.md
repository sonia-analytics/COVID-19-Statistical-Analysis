# COVID-19 Statistical Analysis

## Project Overview
This project applies **parametric and non-parametric statistical methods** to global COVID-19 datasets. The goal is to analyze trends, distributions, and correlations in the pandemic data while building **reproducible workflows**.

## Features
- Parametric analyses: t-tests, ANOVA, regression modeling
- Non-parametric analyses: Mann-Whitney U test, Kruskal-Wallis test
- Interactive and static visualizations using Matplotlib and Seaborn
- Reproducible Jupyter notebooks with clear documentation

## Folder Structure
COVID-19-Statistical-Analysis/
├── data/ # Raw and processed datasets
├── notebooks/ # Jupyter notebooks with statistical analyses
├── visuals/ # Charts, graphs, and workflow screenshots
├── requirements.txt # Python dependencies
└── README.md

 
## Analysis Summary
### 1. Data Overview
- **Datasets:** Global COVID-19 cases, deaths, recoveries, and vaccination data  
- **Sources:** Our World in Data (OWID), Johns Hopkins University  
- **Processing:** Missing values handled, categorical variables encoded, and time-series aligned  

### 2. Parametric Analysis
- Conducted **t-tests** to compare mean daily cases across regions  
- Performed **ANOVA** to evaluate differences between multiple countries  
- Built **linear regression models** to predict daily case trends  

**Example Visualization:**  
![Parametric Analysis Plot](visuals/parametric_example.png)  

### 3. Non-Parametric Analysis
- Used **Mann-Whitney U test** to compare distributions of cases between two countries  
- Applied **Kruskal-Wallis test** for multi-group comparisons  

**Example Visualization:**  
![Non-Parametric Analysis Plot](visuals/nonparametric_example.png)  

### 4. Workflow & Reproducibility
- All notebooks are fully reproducible with documented code blocks  
- Data processing, analysis, and visualization steps are modular  
- Example workflow screenshot:  
![Workflow Screenshot](visuals/workflow_screenshot.png)  

## Getting Started
1. **Clone the repository**
```bash
git clone https://github.com/YOUR_USERNAME/COVID-19-Statistical-Analysis.git 
