meteor-bootstrap3-sass
======================

Meteor package for Bootstrap 3 with Sass support

To install
----------

```sh
$ meteor add reywood:bootstrap3-sass
```

To use
------

To activate bootstrap styles on your site, add the following line to the top of your main scss file:

```scss
@import '.meteor/local/build/programs/server/assets/packages/reywood_bootstrap3-sass/bootstrap';
```

Be sure to add the appropriate tags (as [recommended by Bootstrap](http://getbootstrap.com/getting-started/#template)) to your document `<head>` somewhere in your HTML. Where you add these tags is dependent on how your meteor project is structured.

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

--------------------------------------------------------

If you find a bug or would like to see an improvement made, please [file an issue on GitHub](https://github.com/reywood/meteor-bootstrap3-sass/issues).
