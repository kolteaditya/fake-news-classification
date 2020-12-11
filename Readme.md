# Fake News Classification


The main portions which take the most amount of time are the data pre-processing, the logistic regression classifier and the 
decision trees classifier. Each classifier has 2 modes (TF-IDF and CountVectorizer). It is faster to only run one at a time,
but if you just want to see all the results at once, uncomment the TF-IDF portion of each classifier.

-----------------------------
Important Variables

At the top of the file you will find the training_path variable, which should be changed to point to the train.csv file
on your local machine.

in the data processing section you can change the TRAINING_TO_TEST_RATIO, ngram_min, and ngram_max variables to your choosing.
However, increasing the ngram_max variable will greatly increase the amount of time it takes for the code to run.
--------------------------
Other information

By default, the TF-IDF version of the classifiers is commented out since the CountVectorizer gave better results overall.
You can uncomment the "print" statement and the call to the classification function for each classifier if you wish to
investigate the results.
