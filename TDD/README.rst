
top_words_twitter_account_counter

Gets the text written on each tuit of one account and shows the top 20 used words.

@Authors

Álvaro Lalinde 

Javier Lima

Rafael Rey

Rafael Manzano


To install the dependencies
Check requirements.txt

  >>> pip install -r requirements.txt
  >>> import nltk
  >>> nltk.download('stopwords')
  
Add own creedentials
Add as in the example your own Twitter developer credentials to use the app.
Open the 'file' with a text editor and replace the text between ''.


api = twitter.Api(  'ACCESS_TOKEN_KEY',
                  
                     'ACCESS_TOKEN_SECRET',

                     'CONSUMER_KEY',

                     'CONSUMER_SECRET')

Execute tests

Open the termial

All: tests

  >>> <rutaproyecto> Python -m pytest tests/ -v
  
One test:

  >>> <rutaproyecto> Python -m pytest tests/test_twitter_word_counter.py -v
  
  
Execute attepm

Open the termial

  >>> <rutaproyecto>/top_20_tweets_counter.py
