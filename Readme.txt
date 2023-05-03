This is a Production Level chatbot Flask app that uses PyTorch neural networks to generate responses to user queries. 
Skills Used:
Flask: Python web framework used to build the chatbot application.
PyTorch: Python machine learning library used to build the neural network model.
HTML: Markup language used to structure the chatbot interface.
JavaScript: Programming language used to add interactivity to the chatbot interface.
Jinja2: Template engine used to render the HTML templates.
Natural Language Processing (NLP): Techniques used to preprocess the data and train the neural network model.
app.py: The Flask application.
templates/base.html: The Jinja2 template for the chatbot interface.
static/js/app.js: The JavaScript code for the chatbot interface.
model.py: The PyTorch neural network model.
train.py: The script for preprocessing the data.
nltk_utils.py: This function is used for preprocessing text data and creating useful representations for machine learning models.
The tokenize function uses the nltk library to split a sentence into individual tokens (words, punctuation, or numbers).
The stem function uses the Porter stemming algorithm to reduce words to their root form. This can be useful for tasks such as sentiment analysis or 
document classification.
The bag_of_words function creates a "bag of words" representation for a given sentence. It takes in a list of tokenized words and a list of
known words, and outputs an array of 1's and 0's indicating whether each known word appears in the sentence. 
This can be useful for machine learning tasks such as text classification.
To customize the dataset, you need to modify the intents.json file. This file contains a list of user queries and the corresponding responses.
style.css: To style the chatbot.
