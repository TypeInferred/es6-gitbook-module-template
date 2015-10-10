# ES6 Library Template

This is a template for making an ES6 library.

## Features

* ES6 via [Babel](https://babeljs.io/)
* Documentation via [Gitbook](https://www.gitbook.com/)
* API documentation via [Esdoc](https://esdoc.org/)
* Testing via [Mocha](https://mochajs.org/) and [Chai]()

## Assumptions

* The `package.json` file assumes that you'll be using [Github](http://github.com) to host your project code.

## To use as a template for your own project

Run the following commands:

    git remote add template https://github.com/TypeInferred/es6-gitbook-module-template
    git fetch template
    git merge template/master
    npm install replace
    ./node_modules/.bin/replace 'PROJECT' '<YOUR_GITHUB_PROJECT_NAME>' . -r
    ./node_modules/.bin/replace 'OWNER' '<YOUR_GITHUB_USER_OR_ORG>' . -r

## To build

    npm run build

## To publish

    npm publish