# Credit_Risk_Analysis

## Overview 
Credit risk based on transaction is diffcult to predict as sample size for good transcation is about a hundreds times bigger than smaple size of fradulant transcations. In this assignment the task is to adjust samples and test it that if provided result is reliabe and to what degree. There are multiple ways to split data to minimize biases in analysis. However, all thos analysis follow a common workflow as below: 
1. Load data in dataframe 
2. Split data into training and testing
    a. Training data is the data to adjusted minimize biases 
    b. Test data to ensure that our training data is functioning as intended. 
3. Run analysis
    a. Oversampling is where you add data to smaller set to meet the size of larger set. There are two way to do that random and SMOTE. 
    b. Undersampling is where you remove data from larger sample so it will be size of smaller set. It can be random or  cluster centroid. 
    c. SMOTEEN is were you combine SMOT and and Edited Nearest Neigbors algorithems. 

## Results

### Naive Random Oversampling
![](./images/1.PNG)


### SMOTE Oversampling 
![](./images/2.PNG)

### Undersampling
![](./images/3.PNG)


### Combination
![](./images/4.PNG)


### SMOTEEEN
![](./images/5.PNG)


### Summary 








