# CSS MIN WIDTHS

  Mobile-first classes for css-min-widths.
  Set the desired css-min-widths on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-min-widths
```
View on [npm](https://www.npmjs.org/package/css-min-widths)


## File Size

870B min-widths.css
706B min-widths.min.css 
183B minified and gzipped

## The Code
```
.mn-wi-max  { min-width: max-content; }
.mn-wi-min  { min-width: min-content; }
.mn-wi-fit  { min-width: fit-content; }
.mn-wi-fill { min-width: fill-available; }

@media screen and (min-width: 48em) {
  .mn-wi-max-ns  { min-width: max-content; }
  .mn-wi-min-ns  { min-width: min-content; }
  .mn-wi-fit-ns  { min-width: fit-content; }
  .mn-wi-fill-ns { min-width: fill-available; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .mn-wi-max-m  { min-width: max-content; }
  .mn-wi-min-m  { min-width: min-content; }
  .mn-wi-fit-m  { min-width: fit-content; }
  .mn-wi-fill-m { min-width: fill-available; }
}

@media screen and (min-width: 64em)  {
  .mn-wi-max-l  { min-width: max-content; }
  .mn-wi-min-l  { min-width: min-content; }
  .mn-wi-fit-l  { min-width: fit-content; }
  .mn-wi-fill-l { min-width: fill-available; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

