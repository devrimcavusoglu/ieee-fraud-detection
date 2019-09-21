# cis-fraud-detection
This repo is here reffering to the kaggle competition https://www.kaggle.com/c/ieee-fraud-detection

Evaluation Metric
-----------------
Submissions are evaluated on area under the ROC curve between the predicted probability and the observed target.

How to: https://scikit-learn.org/stable/modules/generated/sklearn.metrics.roc_auc_score.html

Examples
--------

	import numpy as np
	from sklearn.metrics import roc_auc_score
	y_true = np.array([0, 0, 1, 1])
	y_scores = np.array([0.1, 0.4, 0.35, 0.8])
	roc_auc_score(y_true, y_scores)
	>>> 0.75
