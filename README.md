# Steering Torque Prediction
The project uses machine learning algorithms to predict the steering angle and steering torque for any given vehicle speed and turn radius. The dataset used in the project is generated from the experimental measurement of steering toques for an All-Terrain Vehicle.

The dataset discussed above is used to train and test the machine learning algorithm used for the final predictions. Google Colab platform can used to run the code. The code is divided into two program files. The first program predicts the required steering angle and part two predicts the required motor speed (For a 500 W DC Motor). The output of the first program is given as the input for the second program. The ultimate goal of the project is to predict a motor speed that can generate the required torque needed to turn the steering wheel/column as required by the given road conditions and vehicle velocity. The parts of the code and their results are discussed below.

<h2>Steering Angle Prediction</h2>

The program for steering angle determination predicts a value of steering angle required for a given value of turn radius. The code for steering angle prediction was run in Google Colabe. Two methods of regression are used for prediction-Linear regression and Polynomial regression. The comparison of predictions made by both the methods is shown below.

![Steering_Angle_Prediction](https://user-images.githubusercontent.com/47554552/147251691-67318e86-7c8b-4310-9fc8-8722c0a3eddc.jpeg)

<h2>Motor Speed Prediction</h2>

The program for motor speed determination predicts a value of motor RPM required for a given value of steering torque which is in turn determined by the value of steering angle predicted by the algorithm for steering angle prediction. The steering torque is predicted based on the given values of steering angle and vehicle speed. The value of steering torque is used to predict the required motor speed at a constant power of 500 W. Thus accuracy of torque prediction determines the accuracy of motor speed prediction The code for motor speed prediction can be run in Google Colab and the results are discussed here. Two methods of regression are used for prediction-Linear regression and Polynomial regression. The comparison of predictions made by both the methods is shown below.

![Motor_Speed_Prediction](https://user-images.githubusercontent.com/47554552/147252593-b4742f9f-8be9-44e0-b38f-b4b64deea333.jpeg)

<h2>Steps to run the code</h2>

1. Check the name and path of the dataset specified in the code.
2. The Dataset given is fully detailed for the purpose of clear understanding. Remove all columns except the input variable and the predicted variable before running the code.
3. Run the code on Google Colab.
