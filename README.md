# house-price-prediction

### Description
The dataset used on this predictive model is the result of the work of the the StatLib library about housing values in suburbs of Boston. This dataset can be accessed from the following website: [Boston Housing Data](https://archive.ics.uci.edu/ml/machine-learning-databases/housing/)

##### List of Features

```
1) CRIM :     per capita crime rate by town
2) ZN :       proportion of residential land zoned for lots over 25,000 sq.ft.
3) INDUS :    proportion of non-retail business acres per town
4) CHAS :     Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
5) NOX :      nitric oxides concentration (parts per 10 million)
6) RM :       average number of rooms per dwelling
7) AGE :      proportion of owner-occupied units built prior to 1940
8) DIS :      weighted distances to five Boston employment centres
9) RAD :      index of accessibility to radial highways
10) TAX :     full-value property-tax rate per $10,000
11) PTRATIO : pupil-teacher ratio by town
12) B :       1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
13) LSTAT :   % lower status of the population
```

##### Dependent Variable

```
14) MEDV :    Median value of owner-occupied homes in $1000's
```

### Dependencies
You can use `pip` or `conda` to install the dependencies:
* tensorflow
* matplotlib
* jupyter
* pandas
* seaborn
* scikit-learn

### Usage
If you want to try this program, download this repo and launch jupyter to run it on your machine. 


### - - - TODO  - - -

* ENVIRONMENT PREPARATION
    * ~~Install library dependencies~~
    * Document installation and usage


* DATA EXPLORATION
    * Add dataset description
    * ~~Preview the structure of the dataset~~
    * ~~Add data visualizations~~


* DATA PREPROCESSING
    * ~~Apply standarization to feature data~~
    * ~~Apply one-hot encoding to categorical data~~
    * ~~Split data into training and testing sets~~
    * Output preprocessed data for faster preloading


* DATA ANALYSIS
    * ~~Define network parameters~~
    * ~~Define network structure~~
    * ~~Add different network configurations~~
        * ~~Define learning rate with different decaying methods~~
        * ~~Set up cost, optimizer, and accuracy function with different configurations~~
    * ~~Define model execution~~
    * ~~Visualize evolution of MSE on training and testing datasets through epoch iteration~~
    * ~~Visualize evolution of loss function~~
    * ~~Visualize evolution of learning rate~~
    * Add log and summary writer
    * Add Tensorboard visualization
    * Add checkpoints for model restoration


* MODEL DEPLOYMENT
    * Load a pretrained model
    * Test it with new data


* OTHERS
    * Update README files
    * Update all nbviewer links
    * Create to-do document
    * Add Tensorflow 1.x, Tensorflow 2.x, keras, tf.keras, and scikit-learn data analysis notebooks
