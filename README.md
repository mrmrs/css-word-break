# css-word-break 0.0.6

Css module of single purpose classes for word break

#### Stats

208 | 16 | 16
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-word-break
```

#### With Git

```
git clone https://github.com/tachyons-css/css-word-break
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-word-break";
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
<link rel="stylesheet" href="path/to/module/css/css-word-break">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   WORD BREAK
*/
.wb-nor { word-break: normal; }
.wb-ba { word-break: break-all; }
.wb-ka { word-break: keep-all; }
.wb-i { word-break: inherit; }
@media screen and (min-width: 48em) {
 .wb-nor-ns { word-break: normal; }
 .wb-ba-ns { word-break: break-all; }
 .wb-ka-ns { word-break: keep-all; }
 .wb-i-ns { word-break: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .wb-nor-m { word-break: normal; }
 .wb-ba-m { word-break: break-all; }
 .wb-ka-m { word-break: keep-all; }
 .wb-i-m { word-break: inherit; }
}
@media screen and (min-width: 64em) {
 .wb-nor-l { word-break: normal; }
 .wb-ba-l { word-break: break-all; }
 .wb-ka-l { word-break: keep-all; }
 .wb-i-l { word-break: inherit; }
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

