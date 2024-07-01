Inorder to perform linear regression for prediction
by below steps
->We train it with a data ,here we use student progress data from kaggle
->We split these data to first train and then to test the prediction
->were there are more than independent feature (y=mx+c) which means there more than one x values
->Where y is 'performance index' and othere features are x
->In x columns except 'extracurricular activities' all are numeric
->In order to convert 'extracurricular activities' which has values 'yes' or 'no' to binaries(1,0) we use replace() function
->Using sklearn with linear regression performing linar regression in these splitted values of y and x as ytrain,y test ans same for x
->And plotting graph between y_pred and y_test using seaborn we can know the accuracy with graphical visualisation
->We then find mean square error ,mean abs error, root(mse) to get the accuracy in mean value 
->We then find residual by subtracting y_tets values by y_pred
