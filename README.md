Heroku buildpack: Nanoc with Nginx
==================================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpack)
for Nanoc with Nginx.

Usage
-----

Just push your nanoc site containing the config.yml file and the Gemfile to Heroku and you're ready to go.

Requirements
------------
Heroku ruby buildpack (https://github.com/heroku/heroku-buildpack-ruby) is required.
It will read your Gemfile to install custom ruby version and gems.


Credits
-------

The buildpack is based on the Nginx buildpack of essh (https://github.com/essh/heroku-buildpack-nginx) and the Nanoc buildpack of bobthecow (https://github.com/bobthecow/heroku-buildpack-nanoc).
