KNN (k-nearest neighbour) model with MNIST data set
->import MNIST data with this code from sklearn.datasets import load_digits and other required pakages as pandas ,etc
->load the data using load_digits() which imports the data of numerical digits data for digit recognition with pixeled(8X8) image
->chabge it to a dataframe using pandas and store in variable
->split the data for training and testing 
->using KNeighborsClassifier() in sklearn pkgs to perform this easier
->using .predict() it checks th distance between k's nearest neighbours
->Inbuilt confusion_matrix() function prints the matrix of test and predicted data and this matrix is plotted graphically for better visualisation using seaborn
->The classification_report() returns the detils and accuracy of our prediction and precision
->these data can be visualised using imshow() to represent it using pixels 
