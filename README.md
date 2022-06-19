# Phishing-Detection-Model
In today’s era, everything is digitized. Every business or organization has its digital presence. As a result, the number of cybercrimes is also at an all-time high and one of the most used cyber-attack is phishing.

Phishing is a type of attack often used to steal user data, including login credentials and credit card numbers. In this attack, the message is made to look as though it comes from a trusted sender. If it fools the victim, they enter their confidential information, often on a scam website.

Today, there are different kinds of phishing techniques that have been developed which are difficult to trace even for an educated person. One of the main challenging issues in this area is to detect phishing with high accuracy. This is because the phishing website and the corresponding website look so similar in appearance.
  
So, to stop this cyber issue we have created a model to check whether the entered website is good or bad. 

# WorkFlow Of The Project
To detect and predict phishing websites, we are proposing an intelligent, flexible, and effective system.
The website can be detected based on some important characteristics like URL and Domain Identity and the common keywords that are used in Good and Bad Websites. 
 
Steps done to make this project-

•	First, we are importing the libraries

•	Then, reading the dataset downloaded from Kaggle

•	Cleaning of the dataset

•	Tokenisation

•	Snowball Stemmer used to generate root words for each token

•	Then, the List is converted to a string

•	Sites are classified into Good and Bad categories

•	Then printing all good and bad common words occurring in a star-like a pattern

•	Installing web driver and Beautiful Soup to extract all ‘a’ and ‘href’ tags simultaneously. 

•	Now the data we have is converted into a vector using CountVectorizer and is further converted into an array

•	Then Splitting the dataset

•	Training of data frame using Logistic Regression

•	Using pipelining we will rearrange the words

•	Splitting the data and then the prediction is done

•	Previous data frame is dumped

•	Now we can predict if there is phishing or not on any website

# Demonstration
[Click Here For the Demonstration](https://drive.google.com/file/d/1mf6xgTBNtrZwWouB5DXUaKrFZwDca3AT/view)

# Screenshot
<p align="center">
  <img height="400px" width="800px" src="/S1.jpg">
  <br>
  <br>
  <br>
  <img height="400px" width="800px" src="/s2.jpg">
</p>



