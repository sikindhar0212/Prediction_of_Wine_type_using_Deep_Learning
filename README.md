# Prediction_of_Wine_type_using_Deep_Learning
Deep learning typically refers to the analysis of big datasets, but to understand its concepts, smaller datasets will be a good starting point-for example, the wine quality dataset from the UCI Machine Learning Repository. This dataset is publicly available and ideal for getting started with deep learning libraries such as Keras, and learning the basics of neural networks.

Overview of Dataset
First, one needs to understand what structure and features this dataset has. It contains 12 variables that provide critical insight into the physicochemical properties of wine. Some of these variables include:

Fixed Acidity: Non-volatile acids found in wine, measured in g/dm³.
Volatile Acidity: Amount of acetic acid, responsible for the vinegar-like taste of wine, measured in g/dm³.
Citric Acid: A powerful fixed acid in wine, refreshing and allowing better flavor stability; it is expressed in g/dm³. Residual Sugar: The sugar which remains after the fermentation process; it is measured in g/dm³. Chlorides: Influences the salty flavors of the wine and are recorded in g/dm³. Free Sulfur Dioxide: SO₂ unbound, used for the preservation of wine, is given in mg/dm³. Total Sulfur Dioxide: Combination of free and bound SO₂; similarly, measured in mg/dm³.
Other features include density, pH, sulphates, alcohol, and a quality rating that ranges between 0 and 10, which is done by the tasters to the given wine.

Objective
By this exercise, you're supposed to learn the essentials of deep learning. From data preprocessing and building architectures to training models - in detail - using Keras.

Necessary Steps for a head start
Load and understand the dataset
Load the data and explore the structure using Pandas. Visualize the missing values, distribution of each feature, and correlations among them in the dataset. Data Preprocessing Scale or normalize the numeric features. Split the data into input variables, X, and a target variable, y, where the target variable is the wine quality scores. Split the dataset into a training set and a test set, preferably in the ratio 80:20. Modelling the Neural Network
Define a Keras sequential model with the following architecture: Input Layer (number of input features) Hidden Layers (with ReLU activation) Output Layer (single node in case of regression, softmax/sigmoid in case of classification) Compilation and Fitting the Model Choose an appropriate loss function: mse for regression, categorical cross entropy for classification. Optimize with any variant of Adam. Train the model with the training dataset and evaluate the performance of the trained model on the test dataset. Model Evaluation
Check the model performance by using different metrics such as MAE or accuracy. Plot learning curves to visualize performance across training epochs. Making Predictions Test the model on unseen data with the purpose of predicting wine quality and discussing the results.
