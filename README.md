# CS-210-Final-Project-FALL-22

Exploratory Data Analysis Regarding Airbnb Ratings in Los Angeles - Group 22



Introduction:

Airbnb is a widely used platform for providing accommodation services, and ratings are a crucial factor for users to choose their accommodation. Therefore, it might be beneficial for both hosts and guests to find out how these ratings are formed. Our aim is to investigate which factors, if any, have direct influence over overall ratings of users’ accommodation experience.

In order to do so, we aim to examine factors such as neighborhood, amenities, price etc. to determine if there is a causation between these factors. In the first step, we will clean our data to dispose of corrupted values and places with low numbers of given ratings. In the aftermath, we will examine the correlations between these factors and the rating of accommodation to conduct and test our hypothesis.


Problem Definition:

It varies from individual to individual what makes a great accommodation experience for them. Since most people choose their accommodation according to the ratings, the question of which factors increase the ratings is important. Some people may look for higher ratings, but their personal preferences for certain features may not always be reflected in the rating of a particular accommodation. So, they usually look for that feature’s quality in the comments section and lose lots of time. Therefore, in this context, our project aims to assist individuals in finding accommodations that align with their specific preferences in a more efficient manner.


Utilized Datasets:

The datasets that we use in our project are taken from the following link http://insideairbnb.com/get-the-data/ under Los Angeles section, namely listings.csv.

In the main dataset, each row consists of the general information of the accommodation such as amenities, number of rooms and beds, rating of accommodation and so on (See Cell 1.1).

Since our point of interest concerns a certain region. In its original form, our dataset included 45815 rows and 75 columns. Since our dataset contains incomplete rows and columns that are irrelevant to our goal, those rows and columns were filtered not just for easing further computations, but also for displaying more readable and more accurate values (See Cells 1.2, 1.3).

Additionally, since we aim to investigate the change in ratings, we have filtered the rows that had null value in their "review_scores_rating" column which had 10579 null values in total. After filtering both the rows and the columns, their number appeared to be 35236 and 21 respectively (See Cell 1.4-1.8).

The data types that the columns included were float, string and integer values (See Cell 2.1). Furthermore, ratings of accommodations and their counts were plotted in Cell 2.2.

