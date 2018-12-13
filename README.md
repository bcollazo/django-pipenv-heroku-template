# django-pipenv-heroku-template
Minimal template for a heroku-ready Python 3 pipenv-enabled Django app

The purpose is to quickly start simple Django apps ready for heroku, without the repetive copy-pasting through the Django Getting Started or the bloat of the Heroku's https://github.com/heroku/python-getting-started tutorial.

## Using
Just clone into a new directory that you choose the name. Remove this .git stuff associated with this repo, start a new .git, create heroku app, and push.

```
$ git clone https://github.com/bcollazo/django-pipenv-heroku-template myappname
$ cd myappname
$ rm -rf .git
$ git init .
$ heroku create myappnameinheroku
$ git push heroku master
```

Now you can develop quickly by using:
```
pipenv install
pipenv shell
python manage.py runserver
```
Edit your index.html, index.css, index.js appropriately, commit, and push! :)