YelpDatabase
============

Yelp Database Challenge
To Run:
1) First you need to make sure you have mysql and the correct jars and the JSON files (yelp_academic_dataset...)
2) Next run FillDatabases.java- this will fill in the restaurants table as well as the reviews table
3) Next run MachineLearning.java - this will run the algorithm on our random created users as well as all the real users in the file (yelp_users_over_100_2.txt)
4) If you want to create a new restaurant graph (change values etc.) run CreateRestaurantGraph.java (it will deserialize it to a file so change that file name accordingly)
5) If you want to rerun the algorithm change MachineLearning to deserialize the appropriate restaurant serialized file
6) If you want to run the GUI, run GUIPresentation.java, you must run MachineLearning.java beforehand to fill the database first!
Thank you! Enjoy!
