# Turkish Sentiment Analysis Service
This service makes emotional analysis of Turkish sentences and classifies them as positive, neutral or negative. By sending text with the Post method, you get a string result.

#### Gef files
```bash
git remote add origin https://github.com/sevvalkahraman/turkishSentimentAnalysisService.git
git pull origin master
```

#### Create an environment

```bash
python -m venv venv
```

#### Activate the environment
```bash
venv\Scripts\activate.bat 
```

#### Deactivate the environment
```bash
venv\Scripts\deactivate.bat
```

#### Install libraries in Requirements file.
```bash
pip install -r requirements.txt
```

#### Run the service
```bash
set FLASK_APP=application.py
flask run
```

#### Post Json 'http://127.0.0.1:5000/'
```json
{
    "text" : "Güzel şeyler oluyor."
}
```


### Reference
[TextBlob](https://textblob.readthedocs.io/en/dev/)
