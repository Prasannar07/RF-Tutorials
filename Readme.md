# Import the libraries
You might need to install the libraries before importing it.
# Load the hitters data
We are using the preprocessed data by using this Python script. 
To download the data or to look at the code used to clean data.
1. Go to  https://github.com/kirenz/regression click on code and download zip.
2. Extract the data files and paste them in your working directory.
3. You can also download the data from my repository.
4. Then run the Hitter_Data_RF file from my repository.
# Expected results
For Random Forest Regression Model.
1. The MSE of the hitter data is 296.37.

2. Feature Importance plot.

![gmsl figure](figs/feature_imp.png)

3. Permutation feature importance plots.

![gmsl figure](figs/permutation_feature_imp.png)

![gmsl figure](figs/permutation_feature_imp_boxplot.png)


For Random Forest Classification Model. 
1. The best params are {'criterion': 'gini', 'max_depth': 7, 'max_features': 'auto', 'n_estimators': 200}.
2. Accuracy on training set is 100%.
3. Accuracy on test set is 89.87%.

4. Feature Importance plot.

![gmsl figure](figs/class_feature_imp.png)

5. Permutation feature importance plots.

![gmsl figure](figs/class_permutation_feature_imp.png)
