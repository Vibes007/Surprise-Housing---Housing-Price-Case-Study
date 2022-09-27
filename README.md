# Housing Case study
> A US-based housing company named Surprise Housing has decided to enter into the Australian market. The company planning to use data analytics to purchase houses at prices lower than their actual prices by predicting the actual prices of the houses.


## Table of Contents
* General information
* Structure of case study
* Conclusions
* Insights
* Final Report
* Technologies used
* References
* contact

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Surprise Housing company wants to purchase houses below their acual prices and flip them on at a higher price. For the same purpose the company has collected the dataset from the sale of houses in australian market.The company is looking at prospective properties to buy to enter into the australian market. So we are required to build a regression model that can predict the prices of the houses using regularization techniques and decide whether to invest in them or not.
- The company wants to find out:
The variables that are significant in predicting the price of a house.
How well those variables describe the price of a house.
- And to determine the optimal value of lambda for ridge and lasso regression.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Structure of case study
- Problem statement
- Business objectives
- Data understanding and cleaning
- Exploring data
- Data preparation
- Model building and evaluation 

         1 linear Regression
         
         2 Ridge Regression
         
         3 Lasso Regression
- conclusion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Insights
- Lotarea and salesprice is positively correlated.
- If masonry veneer area increases the salesprice also increases.
- Salesprice has a positive correlation with Exterior quality.
- Salesprice is positively correlated with Exterior condition.
- Good basement quality leads to higher salesprice.
- Basement condition and exposure is positively correlated with salesprice.
- Salesprice increase with increase in total basement surface.
- Heating quality and salesprice is positively correlated.
- first floor surface area and second floor surface area is positively correlated with salesprice.
- If above ground living area is more than the salesprice increases.
- If full bathrooms above ground is more than salesprice increases.
- Good kitchen quality leads to higher salesprice.
- If total rooms above ground is more the salesprice increases.
- Fireplace quality and salesprice is positively correlated.
- Goodness in garagefinish is positively correlated with salesprice.
- If sizes of garage in car capacity is more than the salesprice increases.
- If garage area is more than salesprice increases.
- first floor surface area and total basement surface area is highly correlated with r value of around +0.8.
- Exterior quality and kitchen quality are highly correlated with r value of around +0.7.
- Total rooms above ground is positively correlated with ground living area with r value of around +0.8.
- Total rooms above ground and bedrooms above ground is positively correlated with r value of around +0.7.
- Basement finished surface area is negatively correlated with basement unfinished surface area.
- Above ground living area has the highest positve correlation with the salesprice.
- Higher the irregularity of the lot shape lower the salesprice.

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Conclusion
From the above metric_table we can see that the ridge and lasso regression performing better than the linear Regression on test data. The performance of ridge and lasso regression is almost similar, but we can prefer lasso regression as it has high r2_score on test and train data, and also has less RMSE value comparing to ridge and normal linear regression.
The top 10 features selected using lasso regression in order wise is,
1.	GrLivArea
2.	OverallQual
3.	MSZoning_FV
4.	MSZoning_RL
5.	MSZoning_RH
6.	MSZoning_RM
7.	TotalBsmtSF
8.	BsmtFinSF1
9.	1stFlrSF
10.	GarageCars

And the top 10 features selected using ridge regression in order wise is,
1.	OverallQual
2.	1STFlrSF
3.	MSZoning FV
4.	GrLivArea
5.	MSZoning RL
6.	MSZoning RH
7.	MSZoning RM
8.	2NDFlrSF
9.	BsmtFinSF1
10.	TotalBsmtSF

## Technologies Used
- Python version 3.8.8
- numpy library version 1.20.1
- pandas library version 1.2.4
- matplotlib library version 3.3.4
- seaborn library version 0.11.1
- scikit-learn library version 0.24.1
- statsmodels version 0.12.2

## References
1. https://www.kaggle.com/snehac47/house-price-prediction-ridge-lasso-regression
2. https://www.youtube.com/watch?v=QpGJq5a5xsU


## Contact
Created by [(https://github.com/Vibes007)] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
