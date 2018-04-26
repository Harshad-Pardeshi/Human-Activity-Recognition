# Human-Activity-Recognition

Human activity recognition plays a significant role in human-to-human interaction and interpersonal relations. Because it provides information about the identity of a person, their personality, and psychological state, it is difficult to extract. The human ability to recognize another person’s activities is one of the main subjects of study of the scientific areas of computer vision and machine learning. As a result of this research, many applications, including video surveillance systems, human-computer interaction, and robotics for human behavior characterization, require a multiple activity recognition system.

As we understand the importance of human activity recognition, have you ever wondered          how your smartphone, smartwatch or wristband knows when you’re walking, running or sitting?

 Well, your device probably has multiple sensors that give various information. GPS, audio (i.e. microphones), image (i.e. cameras), direction (i.e. compasses) and acceleration sensors are very common nowadays.

We will use data collected from accelerometer sensors which was built from the recordings of 30 study participants performing activities of daily living (ADL) while carrying a waist-mounted smartphone with embedded inertial sensors. The objective is to classify activities into one of the six activities performed viz WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING.

Virtually every modern smartphone has a tri-axial accelerometer that measures acceleration in all three spatial dimensions. Additionally, accelerometers can detect device orientation.
In this part of the series, we will train an LSTM Neural Network (implemented in TensorFlow) for Human Activity Recognition (HAR) from accelerometer data.


<b>Problem Statement</b>: Predict Human Activity and classify them into WALKING, WALKING UPSTAIRS, WALKING DOWNSTAIRS, SITTING, STANDING and LAYING </br  >
</br  >
<b>Dataset</b>: Human Activity Recognition </br  >
7352 observations with 128 datapoints taken within 2.56 seconds with 50% carry forwarded in the training dataset. Each datapoint has 9 measurements for:</br  >
•	Body Acceleration X axis </br  >
•	Body Acceleration Y axis </br  >
•	Body Acceleration Z axis </br  >
•	Body Gyroscope X axis </br  >
•	Body Gyroscope Y axis </br  >
•	Body Gyroscope Z axis </br  >
•	Total Acceleration X axis </br  >
•	Total Acceleration Y axis </br  >
•	Total Acceleration Z axis </br  >
 </br  >
<b>Goal</b>: </br  >
•	Showcase that Standard Neural Networks shouldn’t be used to predict Sequential Classification Problem </br  >
•	Implement Deep Neural Networks and prove it to be better than Standard Neural Network for Sequential Classification Problem </br  >
 </br  >
<b>Steps Completed</b>: </br  >
•	Importing data </br  >
•	Exploratory Data Analysis </br  >
•	Implementing Machine Learning algorithms </br  >
 >o	Decision Tree </br  >
 >o	K Nearest Neighbors </br  >
 >o	SVC </br  >
 >o	Gaussian Naïve Bayes </br  >
 >o	Quadratic Discriminant Analysis </br  >
•	Implementing Recurrent Neural Network (RNN) with keras</br  >
•	Implementing Long-Short Term Memory (LSTM) with tensorflow</br  >
•	Created Android App to track Human Activity using Accelerometer and Gyroscope sensors</br  >
 </br  >
<b>Results</b>: </br  >
LSTM has a better accuracy at predicting the human activity as compared to any machine learning algotihm or even RNN. RNN has 81.81% accuracy where as LSTM has 88.97% accuracy</br  >
 </br  >
<b>Future Scope</b>: </br  >
•	Inclusion of third variable to improve prediction accuracy </br  >
•	Android App enhancements with user better interface </br  >
•	Implement flask API to display output on a remote server </br  >
