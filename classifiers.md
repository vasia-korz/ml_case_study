# Results of classification

## Baselines
- ZeroR
![zeror](images/zeror.png)
- OneR
![oner](images/oner.png)


## Tuned
### Decision Tree J48
- no preprocessing
![](images/j48_no_preprocess.png)
- no `PlaceOfBirth`
![](images/j48_no_placeofbirth.png)
- no `Topic`
![](images/j48_no_topic.png)
- no `VisITedResources`
![](images/j48_no_visited.png)
- no `StudentAbsenceDays`
![](images/j48_no_absence.png)
- with best features
![](images/j48_best_features.png)
![](images/j48_with_best.png)
- best features + confidenceFactor = 2
![](images/j48_conf_factor.png)
![](images/j48_best_pic.png)

### Random Forest
- no processing
![](images/rf_no_process.png)
- no without nationality OR place of birth OR (no grade + dummies)
![](images/rf_no_nationality_or_place.png)
- no parent satisfaction + dummies
![](images/rf_no_parent_satisfaction.png)
- no semester + dummies + 14 depth max
![](images/rf_best.png)

### Logistic Regression
- no process
![](images/log_no_process.png)
- no absence
![](images/log_no_absence.png)
- with best features
![](images/j48_best_features.png)
![](images/log_with_best.png)
- best features + ridge 0.7 + conjugateGradient
![](images/log_best.png)

## Untuned
### BayesNet
![](images/bayesnet.png)
### Bagging
![](images/bagging.png)
### AdaBoostM1
![](images/boosting.png)