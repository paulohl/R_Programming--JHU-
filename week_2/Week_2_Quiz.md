# Programming Assignment 1: Quiz    

Graded Quiz. • 30 min
DueNov 14, 2:59 AM EST    

# Congratulations! You passed!    

**Grade received** 100%        **Latest Submission Grade** 100%          **To pass** 80% or higher

1. Question 1. What value is returned by the following call to pollutantmean()? You should round your output to 3 digits.
```r
1 pollutantmean("specdata", "sulfate", 1:10)
```
> 1 / 1 point
> **Correct**
*******


2. Question 2. What value is returned by the following call to pollutantmean()? You should round your output to 3 digits.
```r
1 pollutantmean("specdata", "nitrate", 70:72)
```
> 1 / 1 point
> **Correct**
******


3. Question 3. What value is returned by the following call to pollutantmean()? You should round your output to 3 digits.
```r
1 pollutantmean("specdata", "sulfate", 34)
```
> 1 / 1 point
> **Correct**
********


4. Question 4. What value is returned by the following call to pollutantmean()? You should round your output to 3 digits.
```r
1 pollutantmean("specdata", "nitrate")
```
> 1 / 1 point
> **Correct** 
******


5. Question 5. What value is printed at end of the following code?
```r
1 cc <- complete("specdata", c(6, 10, 20, 34, 100, 200, 310))
2 print(cc$nobs)
```
> 1 / 1 point
> **Correct**
********

6. Question 6. What value is printed at end of the following code?
```r
1 cc <- complete("specdata", 54)
2 print(cc$nobs)
```
> 1 / 1 point
> **Correct**
*******


7. Question 7. What value is printed at end of the following code?
```r
1 set.seed(42)
2 cc <- complete("specdata", 332:1)
3 use <- sample(332, 10)
4 print(cc[use, "nobs"])
5  
```
> 1 / 1 point
> **Correct**
********

8. Question 8. What value is printed at end of the following code?
```r
1 cr <- corr("specdata")                
2 cr <- sort(cr)  
3 set.seed(868) 
4 out <- round(cr[sample(length(cr), 5)], 4)
5 print(out)
```
> 1 / 1 point
> **Correct**
*******


9. Question 9. What value is printed at end of the following code?
```r
1 cr <- corr("specdata", 129)                
2 cr <- sort(cr)                
3 n <- length(cr)                
4 set.seed(197)                
5 out <- c(n, round(cr[sample(n, 5)], 4))
6 print(out)
```
> 1 / 1 point
> **Correct** 
******


10. Question 10. What value is printed at end of the following code?
```r
1 cr <- corr("specdata", 2000) 
2 n <- length(cr)   
3 cr <- corr("specdata", 1000)   
4 cr <- sort(cr)
5 print(c(n, round(cr, 4)))
```            
> 1 / 1 point
> **Correct**
******
