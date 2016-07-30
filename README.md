# ember-ci [![Build Status](https://travis-ci.org/mike-north/ember-ci.svg?branch=master)](https://travis-ci.org/mike-north/ember-ci) [![CircleCI](https://circleci.com/gh/mike-north/ember-ci/tree/master.svg?style=svg)](https://circleci.com/gh/mike-north/ember-ci/tree/master)

Continuious integration tools and goodies for Ember.js apps.

## Installation

You can install this addon using ember-cli

```sh
ember install ember-ci
```

### Travis-CI

#### Setting up to run Chrome instead of PhantomJS 
```sh
ember g travis-chrome
```

### Circle-CI

#### Default
```sh
ember g circle-ci-init
```

#### Test with headless Chrome
```sh
ember g circle-ci-chrome
```

## Contributing

* `git clone` this repository
* `npm install`
* `bower install`

## Running

* `ember serve`
* Visit your app at http://localhost:4200.

## Running Tests

* `npm test` (Runs `ember try:testall` to test your addon against multiple Ember versions)
* `ember test`
* `ember test --server`

## Building

* `ember build`

## Thanks

* [@martndemus](https://github.com/martndemus) for a [gist that inspired the Travis-CI chrome setup](https://gist.github.com/martndemus/79fe2198c628c22b78f4)

For more information on using ember-cli, visit [http://ember-cli.com/](http://ember-cli.com/).
