Heroku buildpack: wkhtmltopdf
=============================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) of wkhtmltopdf(https://wkhtmltopdf.org/).

Usage
-----

Example usage:

```shell
$ heroku create --stack cedar --buildpack https://github.com/MonkeyTech/heroku-wkhtmltopdf-buildpack

# or if your app is already created:
$ heroku buildpacks:add https://github.com/MonkeyTech/heroku-wkhtmltopdf-buildpack

$ git push heroku master
```

based on: https://github.com/dscout/wkhtmltopdf-buildpack