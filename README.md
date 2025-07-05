# Red-Wine-Analysis

This project explores the relationship between chemical properties and the quality of red wine using regression and correlation analysis. The goal is to understand how various components—such as alcohol content, sugar levels, acidity, and sulfur dioxide—affect wine quality and pH levels.

### Project Overview

Red wine quality depends on multiple chemical factors. In this analysis, we focus on identifying how certain variables influence:
- **Wine quality** (rated 3 to 8)
- **pH level** of the wine

The findings aim to support wine producers in optimizing ingredient proportions to achieve better tasting and more marketable wine.

### Dataset

- Source: [UCI Machine Learning Repository – Red Wine Dataset](https://archive.ics.uci.edu/dataset/109/wine)
- Contains 12 quantitative variables:
  - 9 independent variables (e.g., fixed acidity, sugar, alcohol, sulfur dioxide)
  - 3 dependent variables (including quality and pH)

### Methods Used

### 1. **Regression Analysis**
Used to examine how independent variables influence dependent outcomes:
- Example: Fixed Acidity and Total Sulfur Dioxide → Quality
- Example: Alcohol and Sugar → pH Level

### 2. **Correlation Analysis**
Measured the strength of the linear relationship between variables using:
- `cor()` function in R
- ggplot2 for visualization and regression line fitting

### Tools
- **R Studio**
- `lm()` for regression
- `cor()` for correlation
- `ggplot2` for data visualization

### Key Results

- **Fixed Acidity vs. Sulfur Dioxide and Quality**:
  - Negative correlation observed
  - Some outliers present
  - Higher acidity and sulfur dioxide levels are linked with lower quality scores

- **Alcohol vs. Sugar and pH**:
  - Positive regression trend
  - Higher alcohol and lower sugar levels relate to higher pH (less acidic wine)
  - Indicates that quality improves with more alcohol and less sugar

### Insights

- Alcohol plays a major role in determining wine quality
- Sulfur dioxide and acidity need to be balanced carefully
- Correlation and regression visuals offer wine makers actionable insights on how to adjust chemical levels for better wine

### Conclusion

This analysis offers a statistical approach to red wine quality optimization. By identifying which chemical properties have the strongest impact, wine producers can better control quality outcomes. The regression and correlation techniques used here can also be extended to similar food or beverage quality analyses.

### Reference

- UCI Wine Dataset: https://archive.ics.uci.edu/dataset/109/wine
