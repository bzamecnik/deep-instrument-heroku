# deep-instrument-heroku

ML model to classify music instruments from audio - Heroku deployment.

- Instance of this application: http://deep-instrument.herokuapp.com/
- Main repo (with training scripts etc.): https://github.com/bzamecnik/ml/tree/master/instrument-classification


## Run locally

```
python main.py
open http://localhost:5000
```

### Try

Upload an audio clip and see the predicted class.

You can download a few text examples or provide you own clips.

## Deploy to Heroku

Deploy your own instance of this app!

```
$ heroku apps:create [NAME]
$ heroku buildpacks:add heroku/nodejs
$ heroku buildpacks:add heroku/python
$ git push heroku master
```

or more easily via the Heroku Button:

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)
