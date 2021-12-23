# Steering-Torque-Prediction
The project uses machine learning algorithms to predict the steering angle and steering torque for any given vehicle speed and turn radius. The dataset used in the project is generated from the experimental measurement of steering toques for an All-Terrain Vehicle.

The dataset discussed above is used to train and test the machine learning algorithm used for the final predictions. Google Colab platform can used to run the code. The code is divided into two program files. The first program predicts the required steering angle and part two predicts the required motor speed (For a 500 W DC Motor). The output of the first program is given as the input for the second program. The ultimate goal of the project is to predict a motor speed that can generate the required torque needed to turn the steering wheel/column as required by the given road conditions and vehicle velocity. The parts of the code and their results are discussed below.

STEERING ANGLE PREDICTION

The program for steering angle determination predicts a value of steering angle required for a given value of turn radius. The code for steering angle prediction was run in Google Colabe. Two methods of regression are used for prediction-Linear regression and Polynomial regression. The comparison of predictions made by both the methods is shown below.
![alt text](https://github.com/harikrish3n/Steering-Torque-Prediction/blob/main/Steering Angle Prediction.jpeg?raw=true)
