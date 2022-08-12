# IMDb-prediction
Project originally for data mining class, then worked on alone during the Summer in an attempt to optimize it a bit.

The optomized version is in the "New Code" folder, however, I implore whoever is reading to check both files. I created the scraper and the KNN model alone, while having assisstance with the Porter Stemmer.

So far in the "New Code" folder, I only have a Logistic Regression model, but I intend to expand it, specifically with an SVM model as it did give better scores than the Logistic Regression model, but it does not work as consistantly (It is really good at predicting Action movies, but completely blanks out when predicting Drama).

As for some of the results, accuracy is high because, well, if you have a model where 1/8th of the results is one class, even if the model predicts everything as "False". It is important to look at the precision, recall, and f1 scores.
