# Summary of 2_DecisionTree

[<< Go back](../README.md)


## Decision Tree
- **n_jobs**: -1
- **criterion**: gini
- **max_depth**: 3
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

255.0 seconds

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.159718 | nan          |
| auc       | 0.981224 | nan          |
| f1        | 0.930736 |   0.0735294  |
| accuracy  | 0.94822  |   0.0735294  |
| precision | 0.963636 |   0.790698   |
| recall    | 1        |   0.00338028 |
| mcc       | 0.892118 |   0.0735294  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.159718 | nan         |
| auc       | 0.981224 | nan         |
| f1        | 0.930736 |   0.0735294 |
| accuracy  | 0.94822  |   0.0735294 |
| precision | 0.88843  |   0.0735294 |
| recall    | 0.977273 |   0.0735294 |
| mcc       | 0.892118 |   0.0735294 |


## Confusion matrix (at threshold=0.073529)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |              371 |               27 |
| Labeled as 1 |                5 |              215 |

## Learning curves
![Learning curves](learning_curves.png)

## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Kolmogorov-Smirnov Statistic

![Kolmogorov-Smirnov Statistic](ks_statistic.png)


## Precision-Recall Curve

![Precision-Recall Curve](precision_recall_curve.png)


## Calibration Curve

![Calibration Curve](calibration_curve_curve.png)


## Cumulative Gains Curve

![Cumulative Gains Curve](cumulative_gains_curve.png)


## Lift Curve

![Lift Curve](lift_curve.png)



[<< Go back](../README.md)
