# Recommender System

Recommendation system developed for Telecom's competition.
    
The data and information about the competition can be consulted at:

* https://github.com/Datathon2021/Recomendador

You should download:

* train.csv
* metadata.csv

And read the variables description previously to start working. 

After a brief exploratory analysis of the data, we proceeded with the predictive modeling procedure.

The development procedure was:

1. In the first instance, a collaborative recommendation model in which a cold start of recommendation was implemented for users who were not part of the training database through the most popular content.
2. Subsequently, a hyperparameter search is executed with the aim of increasing the predictive efficiency.
3. The implementation of a classification model such as cold start is then explored.
4. Finally, the results obtained were combined to develop a final model.
5. Then the results obtained were interpreted in order to determine if the predictions obtained by the model were correct.
6. It was studied if the popularity bias error was being incurred.

It should be noted that the exercise was carried out not to enter the competition, but some time later to practice this modeling methodology.