#MachineLearning 
previous: [[Introduction Into Machine Learning]]
In machine learning, there are some main components that are important in the process of build the effective model. Each component play crucial role to make sure that the model not only accurate, but also can be relied in real time scenario.

Here are the explanation of each component:

## 1. Data
	Data are the most basic component in machine learning, without data, model cant be train and studied. Data consist of feature(attribute or feature input) and label(result that want to predict). Quality and quantity data affect the model performance. Data must be cleaned, relevant and representative to the problem we want to solve.

Here are the example of data table:
![[dataexample.jpeg]]
## 2. Algorithm
	Algorithm are the producer or method that use to train model with data. Algorithm determine how the model learn and optimize the learning process. Each algorithm has it own way to work and unique optimize technique.

Here are machine learning algorithm diagram:
![[machine_learning_algorithm.png]]
## 3. Model
	Model are the collection of mathematic calculation and rule that are generated from process of pattern learning from data. Model could be any algorithm like linear regression, decision tree, or neural network. This model trained with data to make prediction or classification.
## 4. Feature Engineering
	Feature engineering are the process to convert raw data into a feature that are more relevant and informative for model. it consist of election, transformation, and create new feature from data available. Feature engineer are important to increase model performance. 

Here are Feature Engineering diagram:
![[Feature-Engineering.png]]
## 5. Training
	Training are the process of model learning from data. during training, model process data and renew the parameter to minimize the failure and maximize accuracy. This process consist of data training and often involve splitting data into training set and validation set.

![[high-lelvel-machine-learning-process.png]]
## 6. Evaluation
	Evaluation are the process to evaluate model performance with unused data during training (data test). it involve evaluation metric, like accuracy, precision, recall, and F1-score to determine how good the model in making prediction or classification.
## 7. Hyperparameter Tuning
	Hyperparameter tuning are the process to optimize parameter outside model that could influence model performance. Hyperparameter are set manually or using  automatic searching technique.
## 8. Deployment
	Deployment are the last step when the trained and evaluate model got implemented into production environment for in real application. it involve model integration into system or application that use model to make decision or prediction.

Next 