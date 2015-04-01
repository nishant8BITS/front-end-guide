# Front-end Guide

[![Build Status](https://travis-ci.org/voorhoede/front-end-guide.svg?branch=master)](https://travis-ci.org/voorhoede/front-end-guide)
[![Dependency Status](https://david-dm.org/voorhoede/front-end-guide.svg?theme=shields.io)](https://david-dm.org/voorhoede/front-end-guide)
[![devDependency Status](https://david-dm.org/voorhoede/front-end-guide/dev-status.svg?theme=shields.io)](https://david-dm.org/voorhoede/front-end-guide#info=devDependencies)

Manage your front-end project in unique views and reusable components.

## Kick start

Create your project folder and add a `package.json`. This can be done with:

	$ npm init

**Install all dependencies**

	$ npm install front-end-guide gulp --save-dev

If are running this on an empty folder its recomended that to get the scafolding files. You can do this by running:

	$ node ./node_modules/front-end-guide/lib/scaffolding.js

## Available Tasks

**Deploy locally**

	$ gulp build_guide
	$ gulp serve

**Develop**

This will do the same as above and also watch files for changes and livereload

	$ gulp watch

**Optimize images**

This will optimize **new** images on the assets-raw folder and copy them to assets/images

	$ gulp imagemin

## API

There are a few options that can be set passed to the front-end-guide:

to be defined



## Documentation

* [Authoring templates (HTML)](docs/authoring-templates.md)
* [Authoring styles (LESS/CSS)](docs/authoring-styles.md)
* [Authoring scripts (JS)](docs/authoring-scripts.md)
* [Authoring assets](docs/authoring-assets.md)
* [Creating modules](docs/module-crud.md)