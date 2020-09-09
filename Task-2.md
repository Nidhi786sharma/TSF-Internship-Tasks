# Task-2 
## Supervised Machine Learning Model
 *Problem Statemnet:* 
                        
      In this regression task we will predict the percentage of marks that a student is expected 
      to score based upon the number of hours they studied. This is a simple linear regression 
      task as it involves just two variables.
      
      
  ### Code:
   
   You can download the code from Linear Regression Task-2.ipynb
   
### Dataset:   
   Dataset is given [here](student_scores.csv.csv)



*There are two types of supervised machine learning algorithms:*

* Regression 

* Classification. 

      The former predicts continuous value outputs while the latter predicts discrete outputs.
      For instance, predicting the price of a house in dollars is a regression problem whereas predicting whether
      a tumor is malignant or benign is a classification problem.
      
      
 ## Linear Regression Theory
 
The term "linearity" in algebra refers to a linear relationship between two or more variables. If we draw this relationship in a two dimensional space (between two variables, in this case), we get a straight line.

Let's consider a scenario where we want to determine the linear relationship between the numbers of hours a student studies and the percentage of marks that student scores in an exam. We want to find out that given the number of hours a student prepares for a test, about how high of a score can the student achieve? 
If we plot the independent variable (hours) on the x-axis and dependent variable (percentage) on the y-axis, linear regression gives us a straight line that best fits the data points, as shown in the figure below.

We know that the equation of a straight line is basically:
       
          y=mx+b
        
          Where b is the intercept and m is the slope of the line. 
  So basically, the linear regression algorithm gives us the most optimal value for the intercept and the slope (in two dimensions). 
  The y and x variables remain the same, since they are the data features and cannot be changed. 
  The values that we can control are the intercept and slope. 
  There can be multiple straight lines depending upon the values of intercept and slope.
  Basically what the linear regression algorithm does is it fits multiple lines on the data points and returns the line that results in the least error.

This same concept can be extended to the cases where there are more than two variables. 
This is called multiple linear regression. For instance, consider a scenario where you have to predict the price of house based upon its area, number of bedrooms, 
average income of the people in the area, the age of the house, and so on. In this case the dependent variable is dependent upon several independent variables. 

 
A regression model involving multiple variables can be represented as:
                
                
                y = b0 + m1b1 + m2b2 + m3b3 + ... ... mnbn

This is the equation of a hyper plane. Remember, a linear regression model in two dimensions is a straight line; 
in three dimensions it is a plane, and in more than three dimensions, a hyper plane.



