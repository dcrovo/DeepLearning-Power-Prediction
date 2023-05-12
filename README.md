# DeepLearning-Power-Prediction
A deep learning active power consumption prediction using convolutional neural networks and LSTMs

## Project info and goals
A major challenge is the efficient planning and management of electrical power production. Active power is a measure of the electrical energy consumed or produced in an electrical system at a given time, and its accurate estimation is essential to ensure that electrical energy production matches demand in real time. In addition, active power is one of the key factors that determine the stability and quality of the electric power supplied to consumers. Therefore, the prediction of the overall active power expected to be consumed or produced in the next 24 hours is a critical problem in the planning and management of electric power production. An accurate and reliable solution to this problem can help improve the efficiency and stability of the power grid, as well as reduce the costs and greenhouse gas emissions associated with power generation.

**Goals**
- Predict the future values of a time series using Deep Learning techniques.
- Implement hyperparameter optimization and quantify the effect through performance metrics.

## Approach
For this problem I decided to try a 1d convolutional layer to extract features followed by a LSTM
