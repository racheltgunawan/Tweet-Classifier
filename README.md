# Tweet-Classifier project using pandas and vectorizers

### Overview
This project was created so that I could know more about AI and Machine Learning models. Following my technica project regarding the origins of hate speech, I wanted to see if I could create my own dataset regarding classifying hate speech. I took an already classified datasets from the internet, and trained a Machine Learning model so that I can recreate the algorithm on a new dataset. 

### Methods
1. Clean the data. I removed any punctuation.
2. Put the tweets into a "bag of words."
     - This bag of words was a count vectorizer which counts the amount of times a word appears in a sentence. If the tweet is classified as a hate tweet, then the model will think that the more times that word appears in a tweet, it will most likely be associated with hate comments.
3. Train the model.
     - Imported a logistic regression model

### Results
The article that assisted me with this project achieved an 89% accuracy on their model, while my project ended up achieving a 96% accuracy. This is due to the fact that I added "stop words" into the bag of words. Getting rid of stop words will allow the model to achieve a higher accuracy because it disregards words that are unnecessary such as "and", "the", "this", etc.

![Screen Shot 2023-08-16 at 5 53 33 PM](https://github.com/racheltgunawan/Tweet-Classifier/assets/58867074/0b2507f9-1279-48c7-987b-19bce55607d4)

### Challenges
I had never worked with machine learning models before and this was my first interaction with ML. Because of my lack of prior knowledge for ML and its algorithms, it took me a while to understand how the models work. However, after much researching and reading into documentation, I was able to complete the project with a higher accuracy than I anticipated.
