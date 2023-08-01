# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model                   |   Weight |
|:------------------------|---------:|
| 3_Default_Xgboost       |        2 |
| 4_Default_NeuralNetwork |        1 |

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.110586 | nan          |
| auc       | 0.989242 | nan          |
| f1        | 0.949891 |   0.418862   |
| accuracy  | 0.962783 |   0.418862   |
| precision | 1        |   0.994073   |
| recall    | 1        |   0.00328183 |
| mcc       | 0.922368 |   0.418862   |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.110586 |  nan        |
| auc       | 0.989242 |  nan        |
| f1        | 0.949891 |    0.418862 |
| accuracy  | 0.962783 |    0.418862 |
| precision | 0.912134 |    0.418862 |
| recall    | 0.990909 |    0.418862 |
| mcc       | 0.922368 |    0.418862 |


## Confusion matrix (at threshold=0.418862)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |              377 |               21 |
| Labeled as 1 |                2 |              218 |

## Learning curves
![Learning curves](learning_curves.png)
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
