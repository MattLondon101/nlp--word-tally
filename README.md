# nlp--word-tally
Web application that displays frequencies of English token words.

## Prerequisites:  
Create conda virtual env:
```shell
conda create -n nwt1 python=3.10
```  
For installation of psycopg2-binary (PostgreSQL database adapter for Python)
```
sudo apt install libpq-dev python3-dev
sudo apt install build-essential
```  

## Usage:

In bash, in nlp--word-tally directory, run:
```
conda activate nwt1
pip install -r requirements.txt
python manage.py runserver
```

Go to http://127.0.0.1:5000/

Enter URL (beginning w/ http:// or https://) and press submit to view English token words, as identified by [punkt.english.pickle](https://github.com/MattLondon101/nlp--word-tally/blob/main/nltk_data/tokenizers/punkt/english.pickle) from [Natural Language Toolkit (NLTK)](https://www.nltk.org/), and with [stop words](https://github.com/MattLondon101/nlp--word-tally/blob/main/stop_words.py) filtered out.
&nbsp;


<p align="center">
  <img width="1000" height="1000" src="https://github.com/MattLondon101/nlp--word-tally/blob/main/WordTally.png?raw=true"
</p>
