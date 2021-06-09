# classification-HW

This project uses several machine learning models to predict credit risk using data you'd generally see from P2P lending services that allow investors to 
loan people money without a bank. Credit risk is an inherently imbalanced classification problem (the number of good loans is much larger than the number of at-risk loans);
because of this, different techniques for training and evaluating models with imbalanced classes were employed.

---

## Technologies

This project is written in python and uses various libraries such as sklearn and imblearn. The models used in this project include: logistic regression classifier,
naive random oversampler, SMOTE, cluster centroids, and SMOTEEN.

---

## Findings

When comparing the results of the models in the resampling notebook, I found that they all had extremely similar results and all did a great job classifying high and low risk
loans. Alternatively, when comparing the results of the ensamble classifiers, you'll see that the easy ensemble classifier greatly outperformed the balanced random forest 
classifier. Although, in the end it does'nt really matter because even the easy ensemble classifier did a terrible job predicting the high risk loans which, in this case, are
the most important.
