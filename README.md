# css-min-widths 1.0.5

Css module of single purpose classes for min widths

#### Stats

269 | 16 | 48
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-min-widths
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-min-widths
```

ssh:
```
git clone git@github.com:tachyons-css/css-min-widths.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-min-widths";
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
<link rel="stylesheet" href="http://unpkg.com/css-min-widths@1.0.5/css/css-min-widths.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-min-widths">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/* Media Queries */
/*
   MIN WIDTHS
*/
.mn-wi-max { min-width: -webkit-max-content; min-width: -moz-max-content; min-width: max-content; }
.mn-wi-min { min-width: -webkit-min-content; min-width: -moz-min-content; min-width: min-content; }
.mn-wi-fit { min-width: -webkit-fit-content; min-width: -moz-fit-content; min-width: fit-content; }
.mn-wi-fill { min-width: -webkit-fill-available; min-width: -moz-available; min-width: fill-available; }
@media (min-width: --breakpoint-not-small) {
 .mn-wi-max-ns { min-width: -webkit-max-content; min-width: -moz-max-content; min-width: max-content; }
 .mn-wi-min-ns { min-width: -webkit-min-content; min-width: -moz-min-content; min-width: min-content; }
 .mn-wi-fit-ns { min-width: -webkit-fit-content; min-width: -moz-fit-content; min-width: fit-content; }
 .mn-wi-fill-ns { min-width: -webkit-fill-available; min-width: -moz-available; min-width: fill-available; }
}
@media (min-width: 48em) and (max-width: 64em) {
 .mn-wi-max-m { min-width: -webkit-max-content; min-width: -moz-max-content; min-width: max-content; }
 .mn-wi-min-m { min-width: -webkit-min-content; min-width: -moz-min-content; min-width: min-content; }
 .mn-wi-fit-m { min-width: -webkit-fit-content; min-width: -moz-fit-content; min-width: fit-content; }
 .mn-wi-fill-m { min-width: -webkit-fill-available; min-width: -moz-available; min-width: fill-available; }
}
@media (min-width: 64em) {
 .mn-wi-max-l { min-width: -webkit-max-content; min-width: -moz-max-content; min-width: max-content; }
 .mn-wi-min-l { min-width: -webkit-min-content; min-width: -moz-min-content; min-width: min-content; }
 .mn-wi-fit-l { min-width: -webkit-fit-content; min-width: -moz-fit-content; min-width: fit-content; }
 .mn-wi-fill-l { min-width: -webkit-fill-available; min-width: -moz-available; min-width: fill-available; }
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

