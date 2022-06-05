# Pneumonia-classification

here is an Pneumatic classification code implemented in pytorch ,

i have used a data set from kaggle :https://www.kaggle.com/competitions/rsna-pneumonia-detection-challenge/rules



First of all i have done some preprocessing on the data , the images are in shape (1024,1024) , i resized it to be (224,224) because I used Resnet  . 

Second I have standardized the pixel values into the interval [0,1] , 

Third : i have divided the data into 24000train Images and 2684 validation images , 

forth : storing the images to the corresponding classes 

fifth : applying some data augmentation like: random rotation ,translation



I have used pytorch_lightining for the first time for training 

