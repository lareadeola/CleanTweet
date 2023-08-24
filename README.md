# SWEETS
SWEETS is collection of micro-services and tools used to enable researchers better detect Suicidal Tendencies in User's Tweets. 

# cleantweet
cleantweet is a python library helps in Natural Language Processing tasks especially in the area of preprocessing and cleaning your data fetched from the Twitter API Backend.

## Installation
pip install cleantweet

## Get Started
How to clean your Twitter Object:
Example 1: If the text file containing the Twitter JSON Data is in the same directory as project files.

!pip install cleantweet <br/>
from cleantweet import CleanTweet<br />
import nltk<br/>
nltk.download('punkt')

#### Instantiate the CleanTwitter Object
data = CleanTweet('sample_text.txt')
<br />
#### Call the clean method
print(data.clean())
<br />
#### show_special_characters()
This method shows the special characters contained in the cleantweet object in a list. From here
you can view the amount of special characters, loop through the list to display them. etc

e.g

data = CleanTweet("text.txt") <br/>
data.show_special_characters()

You can view the documentation and more samples on https://pypi.org/project/cleantweet/

# [SWEET](https://sweets.laresamdeola.repl.co)
This is a web application that checks if a User's Tweets has suicidal tendencies. You can test the application here: https://sweets.laresamdeola.repl.co/
