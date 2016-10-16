# deep-instrument-heroku

ML model to classify music instruments from audio - Heroku deployment.

- Instance of this application: http://deep-instrument.herokuapp.com/
- Main repo (with training scripts etc.): https://github.com/bzamecnik/ml/tree/master/instrument-classification

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
