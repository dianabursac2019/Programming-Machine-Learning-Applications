# Programming-Machine-Learning-Applications
Using TF-IDF to convert unstructured text into useful features

PREDICTING CUISINE TYPE THROUGH INGREDIENTS
DSC478 Class Project Code

This project explores recipe data and through of use machine learning techniques aims to understand various patterns, 
food ingredients and their prevalence in different cuisines around the world. 
The analysis utilizes a What’s Cooking data set that is available on the kaggle.com website. 
In the dataset, the recipe id, the type of cuisine, and the list of ingredients of each recipe (of variable length) 
are included. The training data set contains approximately 40k records/recipes while the test data set has approximately 
1k records. 

Since the test data set does not contain a column for cuisine type, 
the train data set is additionally divided into the train and the test sets for classification purpose. 

Since the main scope of this project is to predict cuisine type based on given ingredients, 
supervised leaning algorithms are used; logistic regression and linear support vector classification (linearSVC). 
In addition the clustering method k-means is explored to reveal how a clustering algorithm will differentiate different 
ingredients and gain insight into hidden relationships between ingredients or recipes. 

For visualizing high-dimensional datasets the TruncatedSVD and t-SNE techniques are applied. 
Through the entire project I worked in parallel on two different models: ‘bag of ingredients’ and ‘bag of words’ 
trying to explore how their predictions would differ.
