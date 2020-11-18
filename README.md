# Linear Regression with Spark

# OBJECTIVE

The code shared demonstrates the implementation of Linear Regression with PySpark. 

# DATASET USED

Please find the data used, uploaded to github along with the code.

# TOOLS

Python, PySpark 

# TECHNIQUES

Linear regression is a linear model, e.g. a model that assumes a linear relationship between the input variables (x) and the single output variable (y). More specifically, that y can be calculated from a linear combination of the input variables (x).

When there is a single input variable (x), the method is referred to as simple linear regression. When there are multiple input variables, literature from statistics often refers to the method as multiple linear regression. Simple regression problem (a single x and a single y), the form of the model would be:

**y = B0 + B1*x** 

Different techniques can be used to prepare or train the linear regression equation from data, the most common of which is called Ordinary Least Squares. It is common to therefore refer to a model prepared this way as Ordinary Least Squares Linear Regression or just Least Squares Regression.

## Types of Linear Regression
 
### Simple linear regression
1 dependent variable (interval or ratio), 1 independent variable (interval or ratio or dichotomous)

### Multiple linear regression
1 dependent variable (interval or ratio) , 2+ independent variables (interval or ratio or dichotomous)

### Logistic regression
1 dependent variable (dichotomous), 2+ independent variable(s) (interval or ratio or dichotomous)

### Ordinal regression
1 dependent variable (ordinal), 1+ independent variable(s) (nominal or dichotomous)

### Multinomial regression
1 dependent variable (nominal), 1+ independent variable(s) (interval or ratio or dichotomous)

### Discriminant analysis
1 dependent variable (nominal), 1+ independent variable(s) (interval or ratio)

When selecting the model for the analysis, an important consideration is model fitting.  Adding independent variables to a linear regression model will always increase the explained variance of the model (typically expressed as R²).  However, overfitting can occur by adding too many variables to the model, which reduces model generalizability.  Occam’s razor describes the problem extremely well – a simple model is usually preferable to a more complex model.  Statistically, if a model includes a large number of variables, some of the variables will be statistically significant due to chance alone.
