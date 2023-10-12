# deep-learning-challenge

In module we look at the nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With the knowledge of machine learning and neural networks, use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

### Step 1: Preprocess the Data
1. Determine the target and features for the model
2. Create a feature array, X, and a target array, y by using the preprocessed data
3. Split the preprocessed data into training and testing datasets
4. Scale the data by using a StandardScaler that has been fitted to the training data

### Step 2: Compile, Train and Evaluate the Model
1. Create a neural network model by assigning the number of input features and nodes for each layer using TensorFlow and Keras.
2. Create the first hidden layer and choose an appropriate activation function.
3. If necessary, add a second hidden layer with an appropriate activation function.
4. Create an output layer with an appropriate activation function.
5. Check the structure of the model.
6. Compile and train the model.

### Step 3: Optimize the Model
1. Repeat the preprocessing steps in a new Jupyter notebook 
2. Create a new neural network model, implementing at least 3 model optimization methods

## Report on the Neural Network Model

Overview of the analysis: With the help of machine learning and deep learning, the analysis seeks to select ventures that could result in the best chance of success. 

Results:

Data Preprocessing
The variable(s) are the target(s) for the model: Columns used for targets - Columns used for targets -> 'APPLICATION_TYPE',	'AFFILIATION', 'CLASSIFICATION',	'USE_CASE', 'ORGANIZATION',	'STATUS',	'INCOME_AMT',	'SPECIAL_CONSIDERATIONS',	'ASK_AMT'

The variable(s) are the features for the model: Column used for features -> 'IS SUCCESSFUL'

The variable(s) that should be removed from the input data because they are neither targets nor features: Id columns - 'Name' and 'EIN'

Compiling, Training, and Evaluating the Model

Number of neurons, layers, and activation functions selected for the neural network model: 
3 layers, 
1st hidden layer - 100,
2nd hidden layer - 90,
3rd  hidden layer - 10

Achieved the target model performance? No

Steps taken to increase model performance: Tested by adding and reducing layers and neurons, increased the number of bins and tested on binning different columns. Additionally, increased the number of epochs and batch size. 

Summary: This model aims to improve accuracy however it does not reach the targeted 75% acuracy. Therefore models such as random forest should be tested to see if the accuracy can be increased.
