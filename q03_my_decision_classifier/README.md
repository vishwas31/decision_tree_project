# Decision tree Classifier

In this assignment you will learn to make a decision tree classifier.

## Write a function called `my_decision_regressor` that :
- Uses gridsearch cv and DecisionTreeClassifier.  
- Find predictions for X_test using the model fitted in X_train and y_train.
- Measures r_square and best parameters.

### Parameters :

| Parameter | dtype | argument type | default value | description |
| --- | --- | --- | --- | --- |
| X_train | DataFrame | compulsory | | Dataframe containing feature variables for training|
| X_test | DataFrame | compulsory | | Dataframe containing feature variables for testing|
| y_train | Series/DataFrame | compulsory | | Training dataset target Variable |
| y_test | Series/DataFrame | compulsory | | Testing dataset target Variable |
| param_grid | Dictionary | compulsory | | Values regarding max depth ,max leap nodes,max impurity decrease |
| n_iter_search | integer | optional | 10 | no. of iterations |


### Returns:

| Return | dtype | description |
| --- | --- | --- |
| accuracy | float |Accuracy score of model |
| best_params| dictionary | best parameters selected by model out of param_grid |


We have made your life simpler by having pre-loaded the grid parameters for you.

Note :
- Use random state = 9 in function while using DecisionTreeClassifier.
