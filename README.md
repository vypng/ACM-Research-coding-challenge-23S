# ACM Research coding challenge (Spring 2023)

## Approach & Solution
I decided to try to predict a star's type given its temperature (K) and luminosity (L/Lo). I thought the best and most efficient way to do this is with python libraries such as numpy, pandas, and sklearn, allowing me to easily create and display linear regression models. I first had to make sure I fully understood multivariate regression, though.


## Challenges
The only experience I had with any type of regression model was in the IB Analysis and Solutions course I took during my senior year of high school. Luckily, my Individual Assessment (IA) was a research paper studying exponential and logarithmic regression between two variables, so I was fairly confident in my abilities to create and understand simple regression models. However, I am not familiar with multivariate regression nor am I experienced with numpy, pandas, or sklearn; so, I consulted several resources to help me learn (see [resources consulted](#Resources-Consulted) below).


## Graphs
<img src="https://user-images.githubusercontent.com/97753409/215263814-e2811ec2-e619-4263-b39e-705bd4d83e4f.png" width="400"> <img src="https://user-images.githubusercontent.com/97753409/215263829-8cdc2b01-40ba-42c6-b676-460985305731.png" height="322">

Figure 1 on left, Figure 2 on right

## Improvements
As seen in Figure 2, the plane of best fit suggests that star types can go past type 5, which is impossible for the given dataset. It overestimates many of the points on the scatter plot, indicating that linear regression may not be the strongest way to model the relationship between the three variables. If I were to continue with this challenge, I would try to test the data with different regression models.


## Resources Consulted
Along with official documentation for the libraries I used, these sources helped me throughout my process:
1. [Matplotlib Tutorial 7: Creating 3D Surface Plots with mplot3d](https://www.youtube.com/watch?v=8h2YhqoUsEw)
2. [Professional 3D Plotting in Matplotlib](https://www.youtube.com/watch?v=fAztJg9oi7s)
3. [How to implement Multivariable Regression in Python](https://www.educative.io/answers/how-to-implement-multivariable-regression-in-python)
4. [Fitting plane/surface to a set of data points](https://gist.github.com/amroamroamro/1db8d69b4b65e8bc66a6)
