# SWEETS
SWEETS is collection of micro-services and tools used to enable researchers better detect Suicidal Tendencies in User's Tweets. 

# cleantweet
cleantweet is a python library helps in Natural Language Processing tasks especially in the area of preprocessing and cleaning your data fetched from the Twitter API Backend.

## Installation
pip install cleantweet

## Get Started
How to clean your Twitter Object:
Example 1: If the text file containing the Twitter JSON Data is in the same directory as project files.

!pip install cleantweet

from cleantweet import CleanTweet
import nltk
nltk.download('punkt')

#### Instantiate the CleanTwitter Object
data = CleanTweet('sample_text.txt')

#### Call the clean method
print(data.clean())

You can view the documentation and more samples on pypi.org/project/cleantweet/

# ![SWEET](https://sweets.laresamdeola.repl.co)
This is a web application that checks if a User's Tweets has suicidal tendencies. You can test the application here: https://sweets/laresamdeola.repl.co
