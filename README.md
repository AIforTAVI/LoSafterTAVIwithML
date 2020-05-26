# LoS after TAVI with ML

Objectives: to develop machine learning models that predict between longer (≥ 9 days) and shorter hospital length of stay (LoS). 

Background: patient logistics is important to best handle the increasing number of patients undergoing transcatheter aortic valve implantation (TAVI). Machine learning shows promise in dealing with complex high-dimensional data. 

Methods: a total of 426 consecutive patients undergoing elective TAVI between 2014 and 2016 was randomly split in training and testing sets (75:25). Cases with intrahospital mortality were excluded. A LoS cut-off was set at 9 days, representing the mean length in days at our center. After a 4-fold cross-validation and hyperparameter tuning, the best models were tested on the independent cohort. A machine learning random forest model was chosen. A total of 83 baseline and procedural features were included. To analyze if feature selection had an impact on outcome prediction, an elastic net was performed. Results: feature selection did not penalize the model’s performance (AUC no feature selection = 0.73 vs. AUC after feature selection = 0.75, p= 0.55). Relying on pre-implantation features only, performance was reduced (p<0.001), whereas feature selection did not result in an inferior performance (AUC no feature selection = 0.63, AUC after feature selection = 0.59; p=0.58). Peak cardiac biomarkers and baseline New York Hear Association (NYHA) functional were among the most predictive variables.

Conclusions: Machine learning has the potential to improve patient selection in TAVI. Post-procedural variables play a significant role in predicting LoS. Larger, multicentric and prospective studies are needed to confirm these results.
