# Multiple Linear Regression to predict fish weight

In this project, I compare the results of a multivariable linear regression model to a single linear regression model. The purpose of this notebook is to create a model which can most accurately predict fish weight.

I also test multivariable linear regression assumptions to see if regression is suitable for this data. 

#### The Dataset
This dataset is a record of 7 common different fish species, their weights, lengths, heights, and widths. 

https://www.kaggle.com/datasets/aungpyaeap/fish-market?resource=download

#### Conclusion

After performing multivariable and single variable linear regression, we see surprisingly that the multivariable linear regression model had an adjusted R^2 of 89% whereas the single linear regression had an R^2 of 80%. 

However, given that the dataset failed 3 out of the 5 assumptions for multivariable linear regression, perhaps it is safer to use single variable regression, as the multivariable linear regression may be overfitting. 

Lastly, we see in both our models that weight is underestimated when the width & length of the fish are small.

<img width="530" alt="multi_regression" src="https://user-images.githubusercontent.com/47754826/210423663-9db720e1-775d-435b-b37a-df9933008156.PNG">

 
