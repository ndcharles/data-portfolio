---
layout: page
title: Linear Regression on Lagos Rent
permalink: /linear-regression-lagos-rent.html
github: 
---
![lagos-rent](/images/rent.png)

As part of our practice labs, this task is to scrape contents from [nigeriapropertycentre](https://nigeriapropertycentre.com/for-rent/flats-apartments/lagos/showtype?bedrooms=2"). Afterwards, build a regression model to predict the housing price (rent) in Lagos.

## Method
Rent data was scraped from [nigeriapropertycentre](https://nigeriapropertycentre.com/for-rent/flats-apartments/lagos/showtype?bedrooms=2") using Python and BeautifulSoup and were preprocessed in Excel to inspect the data for irregularities. EDA was then carried out on the data using python in jupyter-lab environment. Encoding of the categorical variables and model building were done in Python using MultiLabelBinarizer and LinearRegression algorithm; respectively.

## Discussions

After splitting, the linear regression model gave a _score_ of **0.71** and an _intercept_ of **5.6758**. This leaves us with a linear model (where 5.6758 is the intercept; X, the independent variable and; m, the model coefficients.)<br>
<pre>y = 5.6758 + mX</pre>

[\[View project on GitHub\]](https://github.com/ndcharles/SGA08_DATASCI/tree/master/lagos_rent)

**Also see:** [Auto MPG Regression](https://github.com/ndcharles/SGA08_DATASCI/blob/master/LinearRegr.ipynb)
This went a step further to use RidgeRegression (normalization algorithm) to perform regression task.