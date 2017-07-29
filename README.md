[jQuery JSON Presenter Plugin](https://github.com/svpease/jquery-json-presenter) - Troubleshooting JSON made easy
================================

The jQuery JSON Presenter Plugin provides drop-in JSON presentation for any and all your JSON objects making troubleshooting and reporting much easier.

## Getting Started

### Downloading the latest changes

The unreleased development files can be obtained by:

 1. [Downloading](https://github.com/svpease/jquery-json-presenter/archive/master.zip) or forking this repository
 2. [Setup the build](CONTRIBUTING.md#build-setup)
 3. Run `grunt` to create the built files in the "dist" directory

### Including it on your page

Include jQuery and the plugin on a page. Then select a form to validate and call the `jsonPresenter` method, providing whatever JSON you want as a plugin option.

```html
<script src="jquery.js"></script>
<script src="jquery.jsonPresenter.js"></script>
<div id="container"></div>
<script>
$("#container").jsonPresenter({
  json: {"foo":"bar"}
});
</script>
```

Alternatively include jQuery and the plugin via requirejs in your module.

```js
define(["jquery", "jquery.jsonPresenter"], function( $ ) {
	$("#container")jsonPresenter({
    json: {"foo":"bar"}
  });
});
```

## Reporting issues and contributing code

See the [Contributing Guidelines](CONTRIBUTING.md) for details.

## License
Copyright &copy; 2014 Steven Pease<br>
Licensed under the MIT license.
