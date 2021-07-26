# User_Activity_Analysis

An online travel agent site stores their data in JSON files. Each row includes all the cities browsed by a user within a session. Given the dataset,
- Build a model to calculate the simialrity score for each pairwise combination of cities. For each city, find the most likely city to be also searched for within the same session
- Based on the similarity score, build a model to classify user sessions into two groups: users with high intent to book a trip and users with low intent to book.

# Result
The travel intent classifier is built based on the assumption that people who are actually planning a trip are more likely to search for cities that are geographically close to each other. Given the assumption, the model predicts that approximately 56% of users are actually planning a trip and 44% have low intent to book.
