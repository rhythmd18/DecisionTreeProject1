# DecisionTreeProject1

## Dataset
The Titanic dataset is a classic and widely-used dataset in the field of machine learning. It contains information about passengers aboard the RMS Titanic, including their age, sex, class, and survival status. The dataset is split into a training set and a test set, allowing us to build and evaluate our decision tree model effectively.

## Decision Tree Model
We begin by training a decision tree model on the Titanic dataset. Decision trees are powerful and interpretable models that recursively split the data into segments, ultimately providing valuable insights into which features are most significant in determining the target variable, i.e., survival in this case. By using decision trees, we aim to achieve high predictive accuracy and understand the underlying patterns of survival aboard the Titanic.

## Cost-Complexity Pruning
To avoid overfitting, which can occur when a decision tree is too complex and captures noise instead of true patterns, we employ cost-complexity pruning. This technique allows us to control the complexity of the decision tree by removing branches that provide little predictive power. The ccp_alpha parameter governs the extent of pruning, with higher values leading to more aggressive pruning.

## Model Selection
In this project, we explore various ccp_alpha values to build multiple pruned decision tree models. We carefully tune this parameter using cross-validation to identify the optimal value that balances model complexity and predictive performance. We aim to select the ccp_alpha value that maximizes the model's accuracy while maintaining a good balance between bias and variance.
