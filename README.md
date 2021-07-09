# WebMarket_Object_Detection
## 1. The data format we have:
![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Images/1.PNG)

## 2. The data format we want :
![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Images/2.PNG)

To modify the csv file to required format:
* First I have read the data.
* Extract the intergers from the `filename` coloumn and created a new coloumn and added into the dataset 
* `Sorted` the whole data from that new coloumn in ascending order.
* See all the step in ![ Modify CSV file ](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Modify%20CSV%20file.ipynb)

## 3. Generating a YOLO v5 PyTorch file for the model

* First Crete an account on ![Roboflow](https://roboflow.com/) and create a project and upload all the images with their annotations

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Images/3.PNG)

* Split the data into `70 (train)-20 (test)-10 (test)` 

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Images/6.PNG)

* export the file in YOLO v5 PyTorch format

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Images/4.PNG)

## 4. Model Selection

The YOLOv5 PyTorch training and architecture conversion was the most notable contribution, making YOLO easier than ever to train, speeding up training time 10x relative to Darknet.

![](https://blog.roboflow.com/content/images/2020/12/image.png)

## 5. Model Training:

Every thing is explained in the ![ Colab Notebook ](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/WebMarket_Scaled_YOLOv4.ipynb)

## 6 Results:
![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(1).jfif)

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(2).jfif)

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(3).jfif)

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(4).jfif)

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(5).jfif)

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(6).jfif)

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(7).jfif)

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(8).jfif)

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(9).jfif)

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(10).jfif)

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(11).jfif)

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(12).jfif)

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(13).jfif)

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(14).jfif)

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(15).jfif)

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(16).jfif)

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(17).jfif)

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(18).jfif)

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(19).jfif)

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(20).jfif)

