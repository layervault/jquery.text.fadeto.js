## Usage

Fade a selection of text to another selection of text using CSS3 transitions, but invoked via JavaScript.

```javascript
$('h1').fadeTo("New Title");
```

You can also give it a few options:

```javascript
$('h2').fadeTo("New Subheading", {
  fadeInLength: 1000,
  fadeOutLength: 2000,
  fadeInEasing: 'ease-in',
  fadeOutEasing: 'ease-out'
});
```

Or event a callback:

```javascript
$('h2').fadeTo("New Subheading", function () {
  alert("We're done!");
});

```

## Installation

Just include `jquery.text.fadeto.js` as a script tag on the page. Bonus points for incorporating it into your asset pipeline.

## About

jquery.text.fadeto.js was originally developed for [LayerVault](http://layervault.com) by [Kelly Sutton](http://kellysutton.com).

You can see more projects from LayerVault in the [LayerVault Cosmos](http://cosmos.layervault.com).
