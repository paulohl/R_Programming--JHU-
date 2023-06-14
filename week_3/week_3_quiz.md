# Week 3 Quiz

Quiz • 30 min
Submit your assignment
Due November 21, 2:59 AM ESTNov 21, 2:59 AM EST
To Pass 80% or higher

  
# Congratulations! You passed!
**Grade received** 80%
**Latest Submission Grade** 80%
**To pass** 80% or higher
*********

1. Question 1. Take a look at the 'iris' dataset that comes with R. The data can be loaded with the code:
```r
1 library(datasets)
2 data(iris)
```

A description of the dataset can be found by running
```r
1 ?iris
```

There will be an object called 'iris' in your workspace. In this dataset, what is the mean of 'Sepal.Length' for the *species virginica*? 
**Please round your answer to the nearest whole number.** 


(Only enter the numeric result and nothing else.)
```r
7
```
> 1 / 1 point
> **Correct**


To get the answer here, you can use 'tapply' to calculate the mean of 'Sepal.Length' within each species.
*********


2. Question 2, Continuing with the "iris" dataset from the previous Question, what R code returns a vector of the means of the variables "Sepal.Length", 
"Sepal.Width", "Petal.Length", and "Petal.Width"?
```r
( ) apply(iris[, 1:4], 1, mean)    
( ) apply(iris, 2, mean)    
(•) apply(iris[, 1:4], 2, mean)    
( ) colMeans(iris)    
( ) apply(iris, 1, mean)    
( ) rowMeans(iris[, 1:4])    
```

> 1 / 1 point
> **Correct**
********



3. Question 3. Load the 'mtcars' dataset in R with the following code
```r
1 library(datasets)
2 data(mtcars)
```


There will be an object names 'mtcars' in your workspace. You can find some information about the dataset by running
```r
1 ?mtcars
```


How can one calculate the average miles per gallon (mpg) by number of cylinders in the car (cyl)? Select all that apply.
```
(•) sapply(split(mtcars$mpg, mtcars$cyl), mean)  **Correct**    
( ) apply(mtcars, 2, mean)    
( ) lapply(mtcars, mean)    
( ) sapply(mtcars, cyl, mean)    
( ) split(mtcars, mtcars$cyl)    
( ) with(mtcars, tapply(mpg, cyl, mean))    
( ) tapply(mtcars$cyl, mtcars$mpg, mean)    
( ) tapply(mtcars$mpg, mtcars$cyl, mean)    
( ) mean(mtcars$mpg, mtcars$cyl)
```

```
You didn’t select all the correct answers
```


4. Question 4. Continuing with the 'mtcars' dataset from the previous Question, what is the absolute difference between the average horsepower
of 4-cylinder cars and the average horsepower of 8-cylinder cars?
(**Please round your final answer to the nearest whole number**. Only enter the numeric result and nothing else.)
```r
127
```
> 1 / 1 point
> **Correct**
*******


5. Question 5. If you run 
```r
1 debug(ls)
```


what happens when you next call the 'ls' function?
(•) Execution of 'ls' will suspend at the beginning of the function and you will be in the browser.
( ) The 'ls' function will execute as usual.
( ) The 'ls' function will return an error.
( ) You will be prompted to specify at which line of the function you would like to suspend execution and enter the browser.
> 1 / 1 point
> *Correct*
********
