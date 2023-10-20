# K Nearest Neighbors Algorithm

### Purpose:
To classify *iris flower species (Setosa, Versicolor, Virginica)* using a KNN classifier model built entirely from scratch without machine learning libraries, only using NumPy. The goal is to learn patterns in flower data and predict species of new/test samples. 


### Dataset: 
The Iris dataset from scikit-learn, containing 150 samples of 3 species described by 4 features - sepal length, sepal width, petal length, and petal width. 

#### Data preprocessing: 
- Feature matrix X extracted from data 
- Target labels y extracted
- Data split into training and test sets

#### Model Building:
1. KNNClassifier class created from scratch taking the number of neighbors (k) as a parameter 
2. Euclidean distance function defined to calculate distances between samples
3. Classifier fit on training data to learn patterns
4. Predictions made on test data

#### Model evaluation:
1. Confusion matrix and accuracy calculated from scratch without libraries

### Key steps:
- The KNN classification algorithm and all code is implemented from scratch without using Scikit-learn or other ML libraries, relying only on NumPy.
- This provides an example of how to build a basic classifier without external libraries.

### Challenges: 
- Choosing the optimal k value
