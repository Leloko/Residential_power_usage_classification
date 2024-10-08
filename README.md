# Residential_power_usage_classification

This is a sample solution to a multinomial classification problem where a timeseries
residential power usage data collected over three years is utilized. The power usage on the
day can be classified into one of the following four classes: weekend, weekday, vacation, or
COVID_lockdown. Data preparation processes that include combining features from different
data files, feature transformation and synthetic minority oversampling are performed on the
data. Three classification models: logistic regression, decision trees, and random forest were
applied and the prediction results were compared. The best overall results in terms of accuracy,
recall, precision, and f1 score were obtained when utilizing the random forest algorithm.

The dataset can be found on this link: [dataset](https://www.kaggle.com/datasets/srinuti/residential-power-usage-3years-data-timeseries). Using this dataset, the goal is to classify power usage
into one of the four categories: weekday, weekend, vacation, or COVID_lockdown. This report
presents the summary of the data preparation process and the ultimate prediction done using
three different classification algorithms. 
