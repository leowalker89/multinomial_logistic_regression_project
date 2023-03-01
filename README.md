# multinomial_logistic_regression_project

Repo for a group project for CS 4442 Advanced Probability and Statistics for Data Science

**Group Members:** Ignacio Luque, Leo Walker, Sarah Millard, and Jackie Vogel

Multinomial Logistic Regression is useful for predicting an outcome that can be one of multiple categories. An example can be predicting the type of disease a patient has based on their symptoms. A bank could also use it to classify a customer as low, medium, or high risk for loans. 

There are some **data requirements** for Multinomial Logistic Regression. The outcome variable has to be categorical with more than 2 levels. The predictor variables can be either categorical or continuous. The relationships between the independent and dependent variables must be linear. The observations/records in the data must be independent of each other, meaning that they should not influence each other. Independent variables should not be highly correlated with each other.

Multinomial Logistic Regression assumes that the data is linear, that all observations are independent, that outcome categories are mutually exclusive, and that there is no multicollinearity between independent variables. We can assess the assumption of linearity by simply looking at a residual vs. fitted plot of the data. The assumption of independence can be assessed using a Durbin-Watson test. We can plot a correlation matrix of the data in order to visually assess multicollinearity. 

Multinomial logistic regression is a statistical method used to predict the probability of categorical outcomes with more than two possible values. It is an extension of logistic regression, which is used for binary outcomes (only two possible values). It does this by using a set of coefficients to weight the predictor variables and then applying a transformation to convert these weighted sums into probabilities for each category. The coefficients are estimated using maximum likelihood estimation, which involves finding the values of the coefficients that maximize the likelihood of the observed data.

Multinomial logistic regression assumes that the relationship between the predictor variables and the outcome variable is linear. The output of the model is a set of probabilities for each possible category of the outcome variable. We can then use these probabilities to make predictions about which category is most likely for a given set of predictor variable values. We can also evaluate the model's performance using metrics like accuracy or cross-entropy loss.

Multinomial logistic regression can be used in many different fields, such as marketing, healthcare, and social sciences, to predict outcomes like consumer preferences, disease diagnoses, and political affiliations. It is a powerful and flexible tool for analyzing categorical data, but it requires careful selection and preparation of predictor variables and careful interpretation of the output.

Additional references can be found at.

[UCLA Multinomial logistic regression](https://stats.oarc.ucla.edu/r/dae/multinomial-logistic-regression/)

[mygreatlearning blog](https://www.mygreatlearning.com/blog/multinomial-logistic-regression/)

[statstest](https://www.statstest.com/multinomial-logistic-regression/)

[bookdown](https://bookdown.org/chua/ber642_advanced_regression/multinomial-logistic-regression.html)

[towards data science medium](https://towardsdatascience.com/multinomial-logistic-regression-in-r-428d9bb7dc70)

[Wikipedia](https://en.wikipedia.org/wiki/Multinomial_logistic_regression)

[National University](https://resources.nu.edu/statsresources/Multinomiallogistic)

[r-bloggers (R reference)](https://www.r-bloggers.com/2020/05/multinomial-logistic-regression-with-r/)

[datacamp (R reference)](https://www.datacamp.com/tutorial/logistic-regression-R)

[datasciencebeginners (R reference)](https://datasciencebeginners.com/2018/12/20/multinomial-logistic-regression-using-r/)
