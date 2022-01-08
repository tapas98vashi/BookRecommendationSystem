# BookRecommendationSystem
Recommendation systems have emerged as a result of the large amount of data available on the Internet. This project proposes developing recommendation systems using soft computing techniques. My Recommendation system will follow the Collaborative based filtering approach. In Collaborative Based Filtering methodology, the user recommendation will not only be based on their likings or purchase history but also will be based on the profiles of other users having similar liking or similar kind of recent purchase history. So, all in one we can understand that an item will be suggested to an individual user based on the ratings of other users with comparable interests to the one being considered.

Inroduction to Recommender Systems:
Recommendation system is an information filtering technique, which provides users with information and important suggestions which they might be interested in. Some important recommendation systems which we use in our day to day lives:
Netflix
Video on demand recommendations

Amazon
Gold standard ecommerce recommendations

LinkedIn
Professional Networking recommendations

Spotify
Music on demand recommendations

Dataset: This dataset contains data from 278,858 users providing 1,149,780 ratings both explicit and implicit about 271,379 books. This dataset can be found at: http://www2.informatik.uni-freiburg.de/~cziegler/BX/.
This dataset comprises of 3 files:
BX-Users
BX-Books
BX-Book-Ratings

My approach:
Step 1: Download the dataset and reading the dataset.
Step 2: Understanding the dataset better by using inbuilt functions such as shape, column, dtypes, etc.
Step 3: Data pre-processing
Cleaning the data and replacing the missing values.
For an example: Replacing null values in publisher as others.
Step 4: Understanding data of users age and year of publications better by some data visualization and sorting, etc
Step 5: Getter the total count of each ratings from 0 to 10 by different users, by visualising data  using Histogram.
Step 6: To ensure more statistical significance, book with less than 100 ratings were excluded before collaborative approach.
Step 7: Merging book data with the rating data with common feature “ISBN No” such that userId, ISBN No, Book ratings, book title all comes into one data frame.
Step 8: Now adding additional condition to decrease the dataset to limit our users data only for the US and Canada (Improved computing speed and solved MemoryError issue)
Step 9: Applied KNN algorithm and calculated correlation to find the nearest possible recommendations.


