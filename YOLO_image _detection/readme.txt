YOLO image detection project

->The data after training , tesing and prediction datas are in https://drive.google.com/drive/folders/1mb4XjRFsx-J2r6CQ8Nl75VGfcNPoXwkJ?usp=sharing
->This trains with the images in test folder and labelled with labbels for naming the detection 
->we use '!yolo' to start the process of yolo and 'task' is used to tell the yolo what task it should do and 'data' for the yaml file which contains path for train and test data
->And epoch is used to make the model process the data for our required number of times for better result and i used 10
-> after training we use detect in 'task' and val in 'mode' for testing 
->then detect as task and predict as mode for predicting other images data
->Using matplot lib plot those losses and epoch while training and validiating
