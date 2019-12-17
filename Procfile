web: gunicorn gettingstarted.wsgi
web: gunicorn myproject.wsgi
web: bundle exec rails server -p $ PORT
web: lein run -m demo.web $ PORT
web: gunicorn hello:app
git add heroku.yml

git commit -m "Add heroku.yml"
heroku stack:set container

git push heroku master
