# Support-Vector-Machine-using-different-kernels
## 1. Abstract
The main objective is to study the Support Vector Machine with different kernels
using Occupancy Detection dataset and finding good accuracy in all the kernels.
## 2. Data set
 The dataset can be obtained using this link(https://archive.ics.uci.edu/ml/machine-learningdatabases/00357/). 
 This is dataset contains 7 attributes (date time, Temperature, Relative Humidity, Light, CO2, Humidity Ratio, Occupancy).  
 This data is collected for every minute and we don’t need ‘date time ‘attribute’, so we remove it from our dataset.
 The occupancy attribute contains 0 or 1(0 for ‘not occupied’, 1 for ‘occupied’) which is the target attribute.
 ## 3. Technologies
 * Jupyter-notebook. 
 * Scikit-learn. 
 * Python programming for implementation.
 ## 4. Implementation
 * Import libraries and load the data from the dataset to the Jupyter-notebook using np.loadtxt().
 * Separate the data in to features and target where target contains only ‘occupancy status’ attribute. 
 * Partition the instances of features and target in to two parts: 1) training, 2) testing.
 * Shuffle the train data of features using random.shuffle(). 
 * Apply the SVM model with ‘linear’ kernel using training data and find accuracy of test data. 
 * Find the number of support vectors by plotting the above SVM model. 
 * Again, apply the SVM model using training data but with ‘rbf’ kernel and LinearSVC(). 
 * Find the accuracy for each of the model and compare the results. 
