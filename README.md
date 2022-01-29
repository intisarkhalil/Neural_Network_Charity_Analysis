# Neural_Network_Charity_Analysis
Machine Learning, Neural Networks and optimization module are used in this project, to create a binary classifier, which will used to predict wheather the applicants that will be funded by the Alphabet Soup (Charitable organization) or not. 
## The Study Design
 Preprocessing the data for the neural network
Compile, Train and Evaluate the Model and optimizing the model
checking models performance
## Results
### Data Preprocessing
Variable that was considered as the target for my model: IS_SUCCESSFUL Column
Variables that were considered features for my model: Every Column except for IS_SUCCESSFUL which is our target and the ones we will drop
Variable that were neither targets or features for the dataset: Columns that I dropeed are EIN, NAME because they will have little to no impact om our outcome
### Compiling, Training and Evaluating the Model
- For the initial neural network model used 2 hidden layers. The first layer had 80 neurons, the second has 30 there is also an output layer. The first and second hidden layer have the "relu" activation function and the activation function for the output layer is "sigmoid."
- For the optimize neural network model we use 3 hidden layers. The first layer had 7 neurons, the second has 14, the third has 21 there is also an output layer. The first third hidden layers have the "relu" activation function and the activation function for the output layer is "sigmoid."
### checking models performance
Was the model able to achieve the target model performance?
The target performance 75%
1. The initial Model: The accuracy was 73.9%.
The steps taken to try and increase model performance
3. The optimize model: The accuracy was 78%
## Summary
The initial neural network had a accuracy score of 73.9%. we optimize our neural network by removing and bucketing some features , this resulting in increaseing the accuracy. 