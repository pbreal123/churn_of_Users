# churn_of_Users

User Churn Analysis for Sparkify - Udacity Capstone Project
In this project, we analyze user data from a music streaming application to predict user churn. The dataset used for this analysis is a 128 MB subset of the full data, and we leverage Apache Spark for efficient data processing and model building.

Churn is identified by user actions such as submitting a downgrade request or confirming cancellation. Users who have performed either of these actions are classified as churned.

To create our predictive model, we calculate the following metrics:

Average number of songs played per session
Total thumbs down interactions
Total thumbs up interactions
Total number of errors encountered
Count of "Add to Playlist" events
Count of "Add Friends" events
Total songs played
The Gradient Boosted Tree Classifier was the most effective model for this dataset, achieving an F1 score of 0.9067.

The code for this analysis is available in the Sparkify.ipynb notebook.

Libraries used:

PySpark
Pandas
Seaborn
Numpy
Matplotlib
