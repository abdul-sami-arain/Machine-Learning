# Machine Learning: <br>

![i am abdul sami](https://user-images.githubusercontent.com/65020391/198527611-c5cf8a4d-ad1d-437b-9f85-c2d8007d9584.png)
![2](https://user-images.githubusercontent.com/65020391/198527638-47a08679-29ab-4469-8def-969bfe805c0d.png)
![3](https://user-images.githubusercontent.com/65020391/198527655-14be746e-9149-453f-b77f-13b47f330b70.png)
![4](https://user-images.githubusercontent.com/65020391/198527671-d365a2e7-d0df-4512-9639-bb58b22d57f5.png)

## Parameters: <br>
- A model parameter is a variable whose value is estimated from the dataset. <br>
- Parameters are the values learned during training from the historical data sets. <br>
- The values of model parameters are not set manually. <br>
- They are estimated from the training data. <br>
- These are variables, that are internal to the machine learning model. <br>
- Co-efficient in a linear or logical regression and weights in neural networks are examples of model parameters. <br>

## Hyperparameters:
- A hyperparameter is a configuration variable that is external to the model. <br>
- It is defined manually before the training of the model with the historical dataset. <br>
- Its value cannot be evaluated from the datasets.<br>
- It is not possible to know the best value of the hyperparameter. They can often be set using heuristics.<br>
- Hyperparameters affect the speed and accuracy of the learning process of the model.<br>
- Learning rate, the value of K in k-nearest neighbors, and batch-size are examples of hyper-parameters.<br>

## Overfitting:
-	A scenario where machine learning tries to learn from the details along with the noise in the data and tries to fit each point on the curve.<br>
-	As the model has very less flexibility, it fails to predict new data points and thus the model rejects every new data point during prediction.<br>
- Reasons:<br>
		    - Data is not clean, having noise<br>
		    - Model has high variance<br>
		    - Size of training data is not enough<br>
		    - The model is too complex<br>
![overfitting](https://user-images.githubusercontent.com/65020391/198529626-5a7aebdd-676c-48cd-afb4-26efb5c26161.png) <br>

## Underfitting:
- A scenario where machine learning model can neither learn the relationship between variables in data nor predict or classify a new datapoint.<br>
- Reasons:<br>
		       - Data is not clean, having noise.<br>
		       - Model has high bias<br>
		       - Size of training data is not enough	<br>
		       - The model is too simple<br>
![underfitting](https://user-images.githubusercontent.com/65020391/198530352-4666c7bb-b21d-4959-9cde-97bad04f3ea5.png)<br>

## Goodfitting:
- A line or a curve that best fits the data is neither overfitting nor underfitting models but just it right.<br>
![goodfitting](https://user-images.githubusercontent.com/65020391/198530537-d69d362f-7e66-438f-b229-efeb2d1b240b.png)

## Regression:
### When we use Regression?
``` Imagine we collected some data and we want to plug that data in xy-plane.We have x-axis and y-axis. The x-axis contains explanotory variable and y-axis contain response variable.When our explainatory variable values are continuous means that it can take any value either int or real then we are going to do something like REGRESSION. When our explainatory variable isn't continuous it could be something like FACTORS and factor contains different levels then we use technique ANOVA(analysis of variance). ```<br>

### What is Regression?
``` Regression analysis is a statistical methodology that utilizes the relation between two or more quantitative variables so that a response or outcome variable can be predicted from others.```<br><br>
```Y = b0 + b1*X + E```<br><br>
```Y: dependent variable, response variable, outcome variable```<br> 
```X: independent variable, predictor variable, explainatory variable```<br> 
```b0: constant or intercept of the line```<br>
```b1: independent variable's slope```<br> 
```E: error term or residuals```<br> 
![reg](https://user-images.githubusercontent.com/65020391/198567439-4417f04a-795b-4ab8-861d-89b999b724d0.png)

## Splitting of Data Set in ML:
we divides our dataset into two subsets:<br>
- training set—a subset to train a model.<br>
- test set—a subset to test the trained model.



  

