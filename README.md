# Nairaland-Topic-Identification
This will help to classify misplaced topice on nairaland forum

I used Seleinium package to extract topics for each section on nairaland made it into a csv file with there labal of there respective section they belong.
Manual checking and lwas done to remove misclassified topics/article, it was not very efficent and fast, so clustering was used to futher isolate outlier for rescpect label section and they were completely eliminated from the dataset.
The clean dataset was then use to train a model which can now be used to predict and validate if an article was rightly placed in the right section when it was created
