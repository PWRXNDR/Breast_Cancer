# Breast_Cancer
This repository contains a jupyter notebook with Breast Cancer predictions made with help of 'Lazypredict()' library to find an optimal model.

"One of my recent projects revolved around analyzing the Breast Cancer dataset from the UCI Machine Learning Repository. This endeavor allowed me to leverage a tool called Lazypredict, which helped streamline the model selection process. Lazypredict offers a quick way to compare a wide array of models to ascertain which might be the most effective for a given dataset.

The project's focus was binary classification, distinguishing between malignant and benign breast cancer cases. For this type of categorical outcome, a classifier was more appropriate than a regressor. Classifiers predict discrete outcomes, while regressors would be used for continuous data.

Despite Lazypredict's convenience, I noted its compatibility issues. It doesn't always play well with the latest versions of Python and various libraries, which can be a hurdle in certain analytical scenarios. Nonetheless, its comprehensive model comparison capabilities provided substantial benefits during my analysis.

After running the Lazyclassifier, which sifts through various models and evaluates their performance, I settled on RidgeClassifierCV. It stood out with its robustness and yielded a high accuracy score of 97.2% on the test set. However, since RidgeClassifier is not a tree-based model, assessing feature importance required a different approach compared to models like RandomForest or XGBoost.

Upon examining the feature importance, certain attributes notably influenced the model's accuracy. The visualization pointed to features like 'concavity_worst', 'area_worst', and 'radius_worst' as having the most significant impact on the predictions. These features likely have strong clinical correlations with the presence of malignancy in breast cancer tumors.

This project was an excellent opportunity to delve into the practicalities of using Lazypredict and underscored the importance of choosing the right tool for model selection. It also highlighted the nuances of interpreting feature importance in non-tree-based models, contributing to a better understanding of the factors that drive accurate predictions in breast cancer diagnosis."
