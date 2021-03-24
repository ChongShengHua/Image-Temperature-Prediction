# Image-Temperature-Prediction

In this project, we are comparing the accuracy of SpinalNet with different setup to perform image temperature prediction. 4 SpinalNet model different setup is used to comparing among each other. Below are the setup for each model:
1. model 1 - classification model with stochastic gradient descent (SGD) optimizer, learning rate are set to 0.01, momentum is 0.5.
2. model 2 - regression model with Adam optimizer, learning rate is 0.01
3. model 3 - classification model with Adam optimizer, learning rate is 0.001
4. model 4 - regression model with Adam optimizer, learning rate is set to 0.01 and gradually reduce to 0.001 and 0.0001


As result, model 3 gives the lowest RMSE among all models.
