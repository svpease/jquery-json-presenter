# Contributing to the jQuery Validation Plugin

## Reporting an Issue

1. Make sure the problem you're addressing is reproducible.
2. Use https://jsbin.com or https://jsfiddle.net to provide a test page.
3. Indicate what browsers the issue can be reproduced in. **Note: IE Compatibilty mode issues will not be addressed. Make sure you test in a real browser!**
4. What version of the plug-in is the issue reproducible in. Make sure it is reproducible after updating to the latest version.

Documentation issues are also tracked at the [jQuery JSON Presenter](https://github.com/svpease/jquery-json-presenter/issues) issue tracker.

## Contributing code

Thanks for contributing! Here's a few guidelines to help your contribution get landed.

1. Make sure the problem you're addressing is reproducible. Use jsbin.com or jsfiddle.net to provide a test page.
2. Follow the [jQuery style guide](http://contribute.jquery.com/style-guides/js)
3. Add or update unit tests along with your patch. Run the unit tests in at least one browser (see below).
4. Run `grunt` (see below) to check for linting and a few other issues.
5. Describe the change in your commit message and reference the ticket, like this: "Demos: Fixed checkbox for expand option for basic demo. Fixes #21".

## Build setup

1. Install [NodeJS](http://nodejs.org).
2. Install the Grunt CLI To install by running `npm install -g grunt-cli`. More details are available on their website http://gruntjs.com/getting-started.
3. Install the NPM dependencies by running `npm install`.
4. The build can now be called by running `grunt`.

## Unit Tests

To run unit tests, just open `test/index.html` within your browser. Make sure you ran `npm install` before so all required dependencies are available.
Start with one browser while developing the fix, then run against others before committing. Usually latest Chrome, Firefox, Safari and Opera and a few IEs.

## Documentation

Please report documentation issues at the [jQuery JSON Presenter](https://github.com/svpease/jquery-json-presenter/issues) issue tracker.

## Linting

To run JSHint and other tools, use `grunt`.
