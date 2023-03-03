# Credit_Risk_Analysis
## Overview
This week's challenge was focused on evaluating credit card risk using supervised machine learning.  We used both oversampling and undersampling techniques, including RandomOverSampler, SMOTE, and Cluster Centroids.  We also used a combination of the two with SMOTEEN.  Our last two, BalancedRandomForestClassifier and EasyEnsembleClassifier, reduced bias.  

## Results 
### Oversampling 
#### Naive Random Oversampling
|   | Predicted False | Predicted True |
| Actually False | 56 | 31 |
| Actually True | 5329 | 11789 |

* Accuracy: 66%
* Precision: 99%
* Recall: 69%

!(classificationreport1.png)

#### SMOTE Oversampling  
|   | Predicted False | Predicted True |
| Actually False | 53 | 34 |
| Actually True | 6129 | 10989 |

* Accuracy: 62%
* Precision: 99%
* Recall: 64% 

!(classificationreport2.png)

### Undersampling - Cluster Centroids 
|   | Predicted False | Predicted True |
| Actually False | 51 | 36 |
| Actually True | 9683 | 7495 |

* Accuracy: 51%
* Precision: 99%
* Recall: 44% 

!(classificationreport3.png)

### Combination (Over and Under) Sampling - SMOTEENN 
|   | Predicted False | Predicted True |
| Actually False | 61 | 26 |
| Actually True | 6802 | 10316 |

* Accuracy: 65%
* Precision: 99%
* Recall: 60% 

!(classificationreport4.png)

### 
## Summary  
