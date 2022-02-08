# Document_classification_Insurance_Reviews
This is a document classification task by using assurance reviews data


This dataset contains reviews published by insurance customers. There are different columns
- date: it contains the date of the publication of the review and the period of the review experience, and it has to be cleaned.
- note: it is the number of stars given by the customer (it should be predicted in the test dataset)
- auteur: the id of the customer
- avis: the review
- assureur: the name of the insurance
- produit: the type of insurance
## Exploratory data analysis
You can explore the data to better understand it:
- you can study and visualize the evolution of the number of stars (by insurance, etc.)
- wordcloud to visualize the frequency of the terms used in reviews (by insurance, etc.)
You can explore the words used in the review and do some cleaning.
## Unsupervised learning
You will create an unsupervised model to better understand the reviews, and create segmentations that you can interpret.
Train a word embedding model and analyze similar words and word analogies.
   
## Supervised learning
You will create different models to predict the number of stars of the review with the training dataset.
And then you will predict the number of stars of the reviews in the test dataset. You will submit your results that will be evaluated with the RMSE metric.
