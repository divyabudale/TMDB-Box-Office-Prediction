# TMDB-Box-Office-Prediction
Objective : The purpose of the project is to predict the overall worldwide box office revenue of the movies. 

Data : The dataset has been collected from TMDB Data points and includes cast, crew, plot keywords, budget, posters, release dates, languages, production companies, and countries. 

Pre-Processing : The dataset provided the opportunity to extract multiple features from a single variable since the columns were available in the list format, data cleaning was performed, aggregate features were generated, nlp features were created from text column and predefined models were used to process the image features. 

Modelling : Cross validation was used to split the train dataset and models were created using LGB. XGB and Catboost. Blending and Stacking was performed on the models as well.
Finally, the results were evaluated using root mean square logarithmic error.


