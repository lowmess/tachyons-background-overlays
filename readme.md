# tachyons-background-overlays 1.1.0

Tachyons module for adding overlays to background images

#### Stats

429 | 32 | 32
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-background-overlays
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/tachyons-background-overlays
```

ssh:
```
git clone git@github.com:tachyons-css/tachyons-background-overlays.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons-background-overlays";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/tachyons-background-overlays@1.1.0/css/tachyons-background-overlays.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/tachyons-background-overlays">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/* Variables */
/* Media queries */
/*

  TACHYONS BACKGROUND OVERLAYS

  Add an overlay to background images.

  Media Query Extensions:
   -ns = not-small
   -m  = medium
   -l  = large

*/
.bg-darken-0 { box-shadow: none; }
.bg-darken-25 { box-shadow: inset 0 0 0 9999px rgba( 0, 0, 0, .25 ); }
.bg-darken-50 { box-shadow: inset 0 0 0 9999px rgba( 0, 0, 0, .5 ); }
.bg-darken-75 { box-shadow: inset 0 0 0 9999px rgba( 0, 0, 0, .75 ); }
.bg-lighten-0 { box-shadow: none; }
.bg-lighten-25 { box-shadow: inset 0 0 0 9999px rgba( 255, 255, 255, .25 ); }
.bg-lighten-50 { box-shadow: inset 0 0 0 9999px rgba( 255, 255, 255, .5 ); }
.bg-lighten-75 { box-shadow: inset 0 0 0 9999px rgba( 255, 255, 255, .75 ); }
@media screen and (min-width: 30em) {
 .bg-darken-0-ns { box-shadow: none; }
 .bg-darken-25-ns { box-shadow: inset 0 0 0 9999px rgba( 0, 0, 0, .25 ); }
 .bg-darken-50-ns { box-shadow: inset 0 0 0 9999px rgba( 0, 0, 0, .5 ); }
 .bg-darken-75-ns { box-shadow: inset 0 0 0 9999px rgba( 0, 0, 0, .75 ); }
 .bg-lighten-0-ns { box-shadow: none; }
 .bg-lighten-25-ns { box-shadow: inset 0 0 0 9999px rgba( 255, 255, 255, .25 ); }
 .bg-lighten-50-ns { box-shadow: inset 0 0 0 9999px rgba( 255, 255, 255, .5 ); }
 .bg-lighten-75-ns { box-shadow: inset 0 0 0 9999px rgba( 255, 255, 255, .75 ); }
}
@media screen and (min-width: 30em) and (max-width: 60em) {
 .bg-darken-0-m { box-shadow: none; }
 .bg-darken-25-m { box-shadow: inset 0 0 0 9999px rgba( 0, 0, 0, .25 ); }
 .bg-darken-50-m { box-shadow: inset 0 0 0 9999px rgba( 0, 0, 0, .5 ); }
 .bg-darken-75-m { box-shadow: inset 0 0 0 9999px rgba( 0, 0, 0, .75 ); }
 .bg-lighten-0-m { box-shadow: none; }
 .bg-lighten-25-m { box-shadow: inset 0 0 0 9999px rgba( 255, 255, 255, .25 ); }
 .bg-lighten-50-m { box-shadow: inset 0 0 0 9999px rgba( 255, 255, 255, .5 ); }
 .bg-lighten-75-m { box-shadow: inset 0 0 0 9999px rgba( 255, 255, 255, .75 ); }
}
@media screen and (min-width: 60em) {
 .bg-darken-0-l { box-shadow: none; }
 .bg-darken-25-l { box-shadow: inset 0 0 0 9999px rgba( 0, 0, 0, .25 ); }
 .bg-darken-50-l { box-shadow: inset 0 0 0 9999px rgba( 0, 0, 0, .5 ); }
 .bg-darken-75-l { box-shadow: inset 0 0 0 9999px rgba( 0, 0, 0, .75 ); }
 .bg-lighten-0-l { box-shadow: none; }
 .bg-lighten-25-l { box-shadow: inset 0 0 0 9999px rgba( 255, 255, 255, .25 ); }
 .bg-lighten-50-l { box-shadow: inset 0 0 0 9999px rgba( 255, 255, 255, .5 ); }
 .bg-lighten-75-l { box-shadow: inset 0 0 0 9999px rgba( 255, 255, 255, .75 ); }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

- [Alec Lomas](http://lowmess.com)

## License

ISC

