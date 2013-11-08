[ng-boilerplate-heroku](https://github.com/agilogy/ng-boilerplate-heroku)

A ng-boilerplate fork ready to be deployed on heroku

***

## Quickstart

This app uses node.js and the buildpack from https://github.com/heroku/heroku-buildpack-nodejs/tree/diet to be easy deployed on heroku.

The buildpack will be soon the default buildpack for node applications, but from now it has to be added as a custom builpack:

	heroku config:set BUILDPACK_URL=https://github.com/heroku/heroku-buildpack-nodejs#diet -a my-node-app
	git commit -am "fakeout" --allow-empty
	git push heroku



