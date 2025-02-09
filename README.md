# Marketing Mix Analysis

This project analyzes the relationship between various marketing spend categories and sales using multiple linear regression. The analysis helps determine which marketing channels contribute most to sales and provides actionable insights for optimizing marketing budgets.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset Format](#dataset-format)
- [Outputs](#outputs)
- [Visualization](#visualization)
- [Future Enhancements](#future-enhancements)
- [License](#license)

---

## Overview

The Marketing Mix Analysis project utilizes statistical regression techniques to evaluate the impact of marketing expenditures across different channels, such as TV, radio, print, search ads, YouTube, and social media, on sales performance. 

### Objectives:
1. Identify the most impactful marketing channels.
2. Quantify the contribution of each channel to overall sales.
3. Provide statistical measures like R-squared, adjusted R-squared, and confidence intervals for coefficients.
4. Visualize insights with plots for better decision-making.

---

## Features

- **Regression Analysis**:
  - Fits a multiple linear regression model to assess the effect of different spend categories on sales.
  - Outputs key statistics such as R-squared, F-statistic, and P-values.
  
- **ANOVA Table**:
  - Summarizes the regression results to measure statistical significance.

- **Coefficient Analysis**:
  - Extracts regression coefficients and confidence intervals to understand the influence of each category.

- **Visualization**:
  - Generates bar plots to show the contribution of spend categories to sales.

---

## Installation

### Prerequisites

- Python 3.8 or later
- Required libraries:
  - `pandas`
  - `statsmodels`
  - `matplotlib`

### Setup

1. Clone the repository:
   ```bash
   git clone <repository-url>
