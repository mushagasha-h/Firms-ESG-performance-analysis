# 📊 ESG Data Analysis and Statistical Testing

# 📌 Project Overview
This Jupyter notebook performs comprehensive ESG (Environmental, Social, and Governance) performance analysis using statistical methods to compare ESG scores across different industry groups and regions.  
The analysis includes descriptive statistics, normality testing, homogeneity of variance assessment, and advanced statistical tests including non-parametric comparisons and post-hoc analysis.

# 📁 Dataset
**Records:** 5,410 companies

## Key Columns
- ESG_Score, ESG_Combined Score, ESG_Controversies Score  
- Environmental, Social, and Governance pillar scores  
- GICS_Industry_Group (21 groups), Region (5 regions), GICS_Industry_Name (74 industries)  
- Company identifiers and geographic data  

# 🧠 Complete Analysis Performed

## 1. Descriptive Statistics 
Comprehensive descriptive statistics were calculated for all ESG metrics

## 2. Assumption Testing

### Normality Tests (Shapiro-Wilk)

### Homogeneity of Variance (Levene's Test)

## 3. Kruskal-Wallis Tests for Group Comparisons
Tested differences across **21 industry groups** and **5 regions** for:

- ESG Controversies Score  
- Environmental Score  
- Social Score  
- Governance Score  

### Industry Group Results

### Regional Results

## 4. Post-Hoc Pairwise Tests with Dunn's Procedure 
Performed following significant Kruskal-Wallis results:

- Dunn’s test with **Bonferroni correction**  
- Controls family-wise error rate  
- Produces matrices identifying significant group-pairs  

## 5. Detailed Industry/Region Comparisons

### Industry Group Analysis (21 groups)
Examples:
- “Insurance” vs “Utilities”  
- “Materials” vs “Retailing”  
- Identified industries with higher/lower ESG performance  

### Regional Analysis (5 regions)
- North America  
- Europe  
- Asia  
- Australia  
- Other  


