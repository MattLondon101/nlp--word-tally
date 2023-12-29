# nlp--word-tally
Web application that displays frequencies of English token words.

In bash, in nlp--word-tally directory, run:
```
python -m venv env 
source env/bin/activate
pip install -r requirements.txt
python manage.py runserver
```

Go to http://127.0.0.1:5000/

Enter URL (beginning w/ http:// or https://) and press submit to view English token words, as identified by [punkt.english.pickle](https://github.com/MattLondon101/nlp--word-tally/blob/main/nltk_data/tokenizers/punkt/english.pickle) from [Natural Language Toolkit (NLTK)](https://www.nltk.org/), and with [stop words](https://github.com/MattLondon101/nlp--word-tally/blob/main/stop_words.py) filtered out.
&nbsp;


<p align="center">
  <img width="1000" height="1000" src="https://github.com/MattLondon101/nlp--word-tally/blob/main/WordTally.png?raw=true"
</p>
