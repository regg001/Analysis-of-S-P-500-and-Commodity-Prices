#  Analysis of S&P 500 and Commodity Prices

Data Science Project analyzing the trends and predictive relationships between the S&P 500 index and major commodities.

This project explores how fluctuations in commodities like gold, oil, and silver relate to the S&P 500. It includes an exploratory version in R and a machine learning-based predictive version in Python.

---

##  Objective

To understand and model the impact of key commodity prices on the U.S. stock market. The project aims to identify patterns and evaluate forecasting potential using different techniques and tools.

---

##  Tools & Technologies

###  R Version
- **Language**: R  
- **Libraries**: `ggplot2`, `dplyr`, `tidyverse`, `lubridate`, `corrplot`, `forecast`, `rugarch`  
- **Data Source**: [Yahoo Finance](https://finance.yahoo.com/)

###  Python Version
- **Language**: Python  
- **Libraries**: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `yfinance`  
- **Methods**: Feature Engineering, Random Forest Regression, Cross-Validation

---

##  Key Insights

### From R Analysis:
- Positive correlation between gold prices and the S&P 500 during specific periods
- Oil price volatility often moves inversely with market performance during economic shocks
- Seasonal trends in commodities can influence stock index movement
- Silver prices show weaker correlation, behaving independently due to supply/demand dynamics


### From Python Model:
- Advanced feature engineering significantly improved model performance
- **Random Forest Regression** achieved:
  - **RMSE:** 52.77  
  - **R² Score:** 0.9976  
- Feature importance analysis highlights the predictive power of oil and gold volatility
- Taiwan Semiconductors(TSMC) Has direct correlation with the performance of the S&P 500 and the NASDAQ
- Pallaidum also has very strong correlation (0.85) with the NASDAQ and 0.86 with TSMC. Due to the high use of palladium in alot of technology, this commodity has strong correlation with both the major indexes. 

---
### Sample Visualizations:
![image](https://github.com/user-attachments/assets/b0b16afe-3d04-4bea-8537-5d2af8a6cf37)

![image](https://github.com/user-attachments/assets/0d8013ab-f5a3-4e1f-8767-89eda7979183)

![image](https://github.com/user-attachments/assets/e3daaa88-5443-4827-ae69-010d987c8290)

![image](https://github.com/user-attachments/assets/c6855804-74af-458c-b0e0-712065c2d48d)






---

##  Repository Contents
-Analysis of S&P 500 and Commodity Prices.rmd – R Markdown notebook containing the  full exploratory analysis

-Analysis of S&P 500 and Commodity Prices.HTML - R Markdown Containing all the important analysis in a neat format.

-Analysis of S&P 500 and Commodity Prices.pdf - Same as the HTML file just in a PDF  

-Final_DAT_301_Finance.ipynb: Juptyer Notebook contain the full project, contains the everything from the R project plus the second iteration with new commodities and tech companies along with random forest algorithm. 

-Final_DAT_301_Finance.pdf: Contains everything from the Juptyer notebook, just in a easy to read format. 

---



## Author

**Reginal Supoint**  
Data Science Student – Arizona State University  
[LinkedIn](https://www.linkedin.com/in/reginal-supoint)  
[Portfolio (Coming Soon)](#)
