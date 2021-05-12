# SVM-simulation-with-regression-model-using-Python
I try to run SVM method based on previous regression model. 

1. First of all importing data [movie_regression.csv](https://github.com/altheanabila/SVM-simulation-with-regression-model-using-Python/blob/main/Movie_regression.csv) and extracting into panda dataframes

![textimage](https://github.com/altheanabila/SVM-simulation-with-regression-model-using-Python/blob/main/pic1.png)


2. Missing value treatment by using mean value

![textimage](https://github.com/altheanabila/SVM-simulation-with-regression-model-using-Python/blob/main/pic2.png)


3. Dummy variable treatment by replacing string value with binary variable

![textimage](https://github.com/altheanabila/SVM-simulation-with-regression-model-using-Python/blob/main/pic3.png)


4. Define X and y variable

![textimage](https://github.com/altheanabila/SVM-simulation-with-regression-model-using-Python/blob/main/pic4.png)


5. train the data using test train split syntax. We only take 20% of available data as testing data

![textimage](https://github.com/altheanabila/SVM-simulation-with-regression-model-using-Python/blob/main/pic5.png)


6. Standardizing data by converting mean and variance of each data into 0 and 1

![textimage](https://github.com/altheanabila/SVM-simulation-with-regression-model-using-Python/blob/main/pic6.png)


7. Predict y value using svm model

![textimage](https://github.com/altheanabila/SVM-simulation-with-regression-model-using-Python/blob/main/pic7.png)


8. Find out the model performance accuracy. R2 for y train prediction and y test prediction stood above 0,5 which indicates a good model

![textimage](https://github.com/altheanabila/SVM-simulation-with-regression-model-using-Python/blob/main/pic8.png)
