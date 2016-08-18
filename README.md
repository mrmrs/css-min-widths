# css-min-widths 0.0.6

Css module of single purpose classes for min widths

#### Stats

206 | 16 | 16
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-min-widths
```

#### With Git

```
git clone https://github.com/tachyons-css/css-min-widths
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-min-widths";
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
<link rel="stylesheet" href="path/to/module/css/css-min-widths">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   MIN WIDTHS
*/
.mn-wi-max { min-width: max-content; }
.mn-wi-min { min-width: min-content; }
.mn-wi-fit { min-width: fit-content; }
.mn-wi-fill { min-width: fill-available; }
@media screen and (min-width: 48em) {
 .mn-wi-max-ns { min-width: max-content; }
 .mn-wi-min-ns { min-width: min-content; }
 .mn-wi-fit-ns { min-width: fit-content; }
 .mn-wi-fill-ns { min-width: fill-available; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .mn-wi-max-m { min-width: max-content; }
 .mn-wi-min-m { min-width: min-content; }
 .mn-wi-fit-m { min-width: fit-content; }
 .mn-wi-fill-m { min-width: fill-available; }
}
@media screen and (min-width: 64em) {
 .mn-wi-max-l { min-width: max-content; }
 .mn-wi-min-l { min-width: min-content; }
 .mn-wi-fit-l { min-width: fit-content; }
 .mn-wi-fill-l { min-width: fill-available; }
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

ISC
