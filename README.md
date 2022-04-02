### Project Title
LA Neighborhoods' segmenting and clustering

### Installation and Setup Instructions
In order to communicate with Foursquare's database, few steps are needed to take:
- create a developers account and obtain client ID
- request a permission to make a connection
  Example: https://foursquare.com/oauth2/authenticate?client_id=YOUR_CLIENT_ID&response_type=code&redirect_uri=https://www.google.com
- copy the ACCESS_TOKEN combination and define it within the code

### Credits
Coursera, IBM Data Science, Capstone Project
https://www.coursera.org/learn/applied-data-science-capstone/home/welcome


### Problem Statement
Create a model to identity optimal locations to open a new business in Los Anegles to target maximum human population and minimal competition.

### Technique used
One-hot encoding, feature engineering & selection, segmenting and k-means clustering, geocoding (to get logitude and latitude)

### Reflection
In this study, I analyzed the relationship between neighborhood’s poverty rate and venue categories using data from Census 2018. Few things were observed, such as the property ownership were higher in white ethnicity populated area, and the most renters were in Asian populated area. High number in renters mean that the businesses are moving in or out from this neighborhood much more often than the area where businesses have their ownership.

