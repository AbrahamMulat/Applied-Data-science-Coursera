### Practice Quiz: Linear Regression and Multiple Linear Regression

1. consider the following lines of code, what is the name of the column that contains the target values:

```python
from sklearn.linear_model import LinearRegression 
lm=LinearRegression()
X = df[['highway-mpg']]
Y = df['price']
lm.fit(X, Y)
Yhat=lm.predict(X)
```

- [x] 'price'
- [ ] 'highway-mpg'



2. consider the following equation:
<img src = "https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/mrc50jdfEeiKpA6ZQCE7wA_d5b99b98180e37f67b0659d10a8104f5_eq.png?expiry=1688947200000&hmac=L4l4pn9GOBW8MojBXPx3mVbp3vms2TpW5arbBXd2FlE">


the variable y is?
- [ ] the predictor or independent variable
- [x] the target or dependent variable
- [ ] the intercept

### Practice Quiz: Model Evaluation using Visualization
1. Consider the following **Residual Plot**, is our linear model correct:
   <img src = "https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/Ul4kvjnnEeiM9Q4Js9CcVg_ced175ed7d43ea88b0ae95751bd3c150_Screen-Shot-2018-04-06-at-6.07.40-PM.png?expiry=1688947200000&hmac=Gwd0_-WhIey0nrfUoIDFUjoCSvibjG_mhu-En3i8eoA">
   - [ ] yes
   - [x] no
