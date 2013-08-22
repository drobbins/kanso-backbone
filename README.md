Kanso-Backbone
--------------

Backbone.js packaged as a [Kanso](http://kan.so) module. See the test branch for example usage.

### Install

Add `modules` to your dependencies section in `kanso.json`.

```javascript
...
  "dependencies": {
    "backbone": null,
    ...
  }
```

Run `kanso install` to fetch the package.


### Usage

```javascript
(function($, Backbone) {
  // backbone can use any DOM library you like
  Backbone.setDomLibrary($);

  // use Backbone like a boss
  ...

  // use require if you use the jquery kanso module
  // or window.$ if you use the stock jQuery
})(require('jquery'), require('backbone'));