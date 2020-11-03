# machine-learning-challenge
Preprocess the Data

Preprocess the dataset prior to fitting the model.
Perform feature selection and remove unnecessary features.
Use MinMaxScaler to scale the numerical data.
Separate the data into training and testing data.


Tune Model Parameters

Use GridSearch to tune model parameters.
Tune and compare at least two different classifiers.


Reporting

I decided to move forward with the recommended Vector Machine Linear Classifier and the GridSearchCV in Model-1, which initiatally gave me a Testing Data Score: 0.8306636155606407 and a Training Data Score: 0.8216669845508296. Once I trained the model with GridSearchCV I was able to improve the score to  0.884030228716553.

To compare, I had decided to use a Random Forest model, since it is widely used for supervised learning, and it uses less time to train given its ability to create multiple decision trees. Despite its recommended use, the accuracy level for this model was only 0.7145308924485125.  
