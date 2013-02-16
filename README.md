# jRuby and sinatra on heroku

## How to use (local)

```
$ rbenv install jruby-1.7.2
$ gem i bundler
$ bundle
$ jruby app.rb

```

## on Heroku

```
$ heroku login (if you not sing-in)
$ heroku create
$ git push heroku master
```

## Docs

https://devcenter.heroku.com/articles/moving-an-existing-rails-app-to-run-on-jruby
