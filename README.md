Two machine learning models (logistic reg vs. randomforest) were built to understand the importance of skills in winning volleyball games. After CV model evaluation the randomforest model performed slightly better over logistic with a final ROCAUC of 0.915 and an accuracy of 0.824. The data used consisted of 76,756 volleyball matches, including metrics on winning and losing players. The data was preprocessed and cleaned using dplyr and the models were built with tidymodels. A binary feature for winner/loser was created to perform classification. The dataset initially included 65 variables, but was narrowed down to nine to focus only on skill metrics.

The data used in this project comes from the tidytuesday:
https://github.com/rfordatascience/tidytuesday/blob/main/data/2020/2020-05-19/readme.md

