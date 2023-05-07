# Titanic
Projects to forecast who will survive based in the departure city  on Titanic shipwreck using pandas, numpy, Min_max_scaler and others tools to see and preprocessing the datas.
We Have two dataset with columns most important year(mean 29 yearsd old), embarked with 3 acronyms Q,S,C (C = Cherbourg, Q = Queenstown, S = Southampton), sex, pclass(The class each passsager), Passager Id, SibSp(Number of siblings / spouses aboard the Titanic), parch(Number of parents / children aboard the Titanic), fare(ticket fare) and survived(target column). The embarked and sex was treated with Label Encoder, all missing values take the mean aech column.
For train the model I use the logistic regression, finally the model has a accuracy to 78% this is not bad because the goal is know what city have the most probably to have people survived.

