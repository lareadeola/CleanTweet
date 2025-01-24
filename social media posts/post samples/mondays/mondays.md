1. Creating a Wordcloud.

You can use the DiagramTweet class to create different diagrams for NLP tasks. To create a Wordcloud using cleantweet, takes two lines of code:

figures = clt.DiagramTweet('file.txt') 
figures.word_cloud()

The first line creates an instance of the DiagramTweet class and the second line calls the word_cloud() method. To know more about the different parameters of the word_cloud() method, you can see it's full definition in the API docs at https://lnkd.in/efuJgwNc

![Wordcloud Example](https://github.com/lareadeola/CleanTweet/blob/main/example%20images/word%20cloud%20example.png)
