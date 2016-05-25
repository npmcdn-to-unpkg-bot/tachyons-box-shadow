# tachyons-box-shadow 1.0.0

box-shadow CSS module for Tachyons

#### Stats

297 | 20 | 20
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-box-shadow
```

#### With Git

```
git clone https://github.com/tachyons-css/tachyons-box-shadow
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons-box-shadow";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/tachyons-box-shadow">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*

  BOX-SHADOW

  Media Query Extensions:
   -ns = not-small
   -m  = medium
   -l  = large

 */
.shadow-1 { box-shadow: 0px 0px 4px 2px rgba( 0, 0, 0, 0.2 ); }
.shadow-2 { box-shadow: 0px 0px 8px 2px rgba( 0, 0, 0, 0.2 ); }
.shadow-3 { box-shadow: 2px 2px 4px 2px rgba( 0, 0, 0, 0.2 ); }
.shadow-4 { box-shadow: 2px 2px 8px 0px rgba( 0, 0, 0, 0.2 ); }
.shadow-5 { box-shadow: 4px 4px 8px 0px rgba( 0, 0, 0, 0.2 ); }
@media screen and (min-width: 48em) {
 .shadow-1-ns { box-shadow: 0px 0px 4px 2px rgba( 0, 0, 0, 0.2 ); }
 .shadow-2-ns { box-shadow: 0px 0px 8px 2px rgba( 0, 0, 0, 0.2 ); }
 .shadow-3-ns { box-shadow: 2px 2px 4px 2px rgba( 0, 0, 0, 0.2 ); }
 .shadow-4-ns { box-shadow: 2px 2px 8px 0px rgba( 0, 0, 0, 0.2 ); }
 .shadow-5-ns { box-shadow: 4px 4px 8px 0px rgba( 0, 0, 0, 0.2 ); }
}
@media screen and (min-width: 48em) and (max-width: 64em) {
 .shadow-1-m { box-shadow: 0px 0px 4px 2px rgba( 0, 0, 0, 0.2 ); }
 .shadow-2-m { box-shadow: 0px 0px 8px 2px rgba( 0, 0, 0, 0.2 ); }
 .shadow-3-m { box-shadow: 2px 2px 4px 2px rgba( 0, 0, 0, 0.2 ); }
 .shadow-4-m { box-shadow: 2px 2px 8px 0px rgba( 0, 0, 0, 0.2 ); }
 .shadow-5-m { box-shadow: 4px 4px 8px 0px rgba( 0, 0, 0, 0.2 ); }
}
@media screen and (min-width: 64em) {
 .shadow-1-l { box-shadow: 0px 0px 4px 2px rgba( 0, 0, 0, 0.2 ); }
 .shadow-2-l { box-shadow: 0px 0px 8px 2px rgba( 0, 0, 0, 0.2 ); }
 .shadow-3-l { box-shadow: 2px 2px 4px 2px rgba( 0, 0, 0, 0.2 ); }
 .shadow-4-l { box-shadow: 2px 2px 8px 0px rgba( 0, 0, 0, 0.2 ); }
 .shadow-5-l { box-shadow: 4px 4px 8px 0px rgba( 0, 0, 0, 0.2 ); }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

MIT

