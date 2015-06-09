my-residence [![Build Status](https://travis-ci.org/ismarslomic/myresidence.svg?branch=master)](https://travis-ci.org/ismarslomic/myresidence) [![Code Climate](https://codeclimate.com/github/ismarslomic/myresidence/badges/gpa.svg)](https://codeclimate.com/github/ismarslomic/myresidence) [![Test Coverage](https://codeclimate.com/github/ismarslomic/myresidence/badges/coverage.svg)](https://codeclimate.com/github/ismarslomic/myresidence/coverage) [![Dependencies](https://david-dm.org/ismarslomic/myresidence.png?theme=shields.io)](https://david-dm.org/ismarslomic/myresidence) [![devDependency Status](https://david-dm.org/ismarslomic/myresidence/dev-status.svg)](https://david-dm.org/ismarslomic/myresidence#info=devDependencies)
============

Web application for administrating your residence such as condominium (nor: boligsameie og borettslag)

### Install dependencies
```bash
sudo npm install
bower install
```

### Use Gulp tasks

* `gulp` or `gulp build` to build an optimized version of your application in `/dist`
* `gulp serve` to launch a browser sync server on your source files
* `gulp serve:dist` to launch a server on your optimized application
* `gulp test` to launch your unit tests with Karma
* `gulp test:auto` to launch your unit tests with Karma in watch mode
* `gulp protractor` to launch your e2e tests with Protractor
* `gulp protractor:dist` to launch your e2e tests with Protractor on the dist files

### Project strucutre based on
[generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular)

### Upgrade npm modules to latest version
```bash
# Install with npm
npm install -g npm-check-updates

# Get list of all upgrades
ncu

# Upgrade all npm modules to latest version and update package.json
ncu -u
```

### Upgrade bower modules to latest version
```bash
# Install with npm
npm install -g bower-update

# Upgrade all bower modules to latest version and update bower.json
bower-update --non-interactive
```
