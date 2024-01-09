# **Walk Run Classification**
-----------------------------

## **Business Case-Study**

This project is based on Human motion analysis and activity recognition using wearable watch/sensors, which help to us to classify human activities (either walking or running) based on sensor data collection from wearable devices. We will apply different Machine learning algorithm including: Decision Tree, Random Forest, Gradient Boosting, XG-Boosting and Artificial Neural Network.

------------

## **Dataset Description**

This Dataset consists Total of 10 Features and 1 Target(activity).

1) Date	: The calendar date on which an activity was recorded.

2) Time	: The specific time of day when an activity was recorded.

3) Username	: The identifier associated with the individual wearing the wristwatch.

4) Wrist :  Indicates the wrist (left or right) on which the wristwatch is worn.

5) Activity : The type of activity being performed (0 for walking/1 for running).

6) Acceleration_x	: Acceleration along the x-axis measured by the wristwatch's accelerometer.

7) Acceleration_y	: Acceleration along the y-axis measured by the wristwatch's accelerometer.

8) Acceleration_z	: Acceleration along the z-axis measured by the wristwatch's accelerometer.

9) Gyro_x	: Angular velocity around the x-axis measured by the wristwatch's gyroscope.

10) Gyro_y : Angular velocity around the y-axis measured by the wristwatch's gyroscope.

11)	Gyro_z : Angular velocity around the z-axis measured by the wristwatch's gyroscope.

-----------

### **Analysis From the Graph**

![image](https://github.com/anjanikmr39/Walk-Run-Classification/assets/67219753/29ec0821-4c7c-4538-a3cf-095cc961b718)


1) Activity is 0 for walking and 1 for running, and wrist is 0 for left hand and 1 for right hand.

2) In accleration_x, running movement is more compared to walking. Also positive value means move right side and negative value means move left side.

3) In accleration_y, walking movement is more compared to running. Also positive value means move forward side and negative value means move backward side.

4) In accleration_z, running movement is more compared to walking. Also positive value means move upward side and negative value means move downward side.

5) We analyse that in gyro_x little bit clockwise rotation is there during walking and anticlockwise rotation is there during running, because gyro positive means anticlockwise rotation and gyro negative means clockwise rotation.

6) We analyse that in gyro_y anticlockwise rotation is there in both during walking and running, but during running movement is more, because gyro positive means anticlockwise rotation and gyro negative means clockwise rotation.

7) We analyse that in gyro_z anticlockwise rotation is there in both during walking and running, but during walking movement is more, because gyro positive means anticlockwise rotation and gyro negative means clockwise rotation.

-------
## **Model Comparison Report**

![image](https://github.com/anjanikmr39/Walk-Run-Classification/assets/67219753/4e14050b-b2ad-48f1-81d6-11cd6ed3faf9)

--------
## **Challenges faced**:

We have to analyse EDA part with respect to acceleration_x, acceleration_y, acceleration_z, gyro_x, gyro_y and gyro_z and have to understand its relation with respect to wrist and activity.

------------

## **More information**
Visit this python file for more detailed analysis [WalkRunClass.ipynb](https://github.com/anjanikmr39/Walk-Run-Classification/blob/master/WalkRunClass.ipynb)
