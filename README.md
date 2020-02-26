# snowdayclassifer


New York City schools have closed for snow 15 times in the last 40 years. When they do, city operations are disrupted; parents must seek other accommodations, students miss out on educational opportunities and access to basic health services and food, and many other challenges arise. As such, a useful predictor for snow days would be critical to municipal preparedness. However, the decision to close schools is not simply a function of snowfall, the climate is changing, and different mayoral administrations seem to handle the issue differently, not to mention control of schools has shifted over the past several decades. I attempt to build a classifier using NOAA weather data, recognizing that success will be measured not in pounds or ounces, but in grams.

This project implements SVM, logistic regression, naive bayes, and KNN. Data are preprocessed and under/over sampled using SMOTE. An f-score with beta=0.5 is used to score the classifiers so as to limit the false negative rate.
