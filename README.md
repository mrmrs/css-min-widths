# css-min-widths

Functional CSS for min-widths

## Filesize

| File | Size |
|------|------|
| `dist/min-widths.css` | 897 bytes |
| `dist/min-widths.min.css` | 667 bytes (170 Gzipped) |

## Install

```sh
npm install css-min-widths
```

## Usage

### Import

```css
@import "css-min-widths";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-min-widths/dist/min-widths.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-min-widths/dist/min-widths.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.mn-wi-max` | `min-width: max-content;` |
| `.mn-wi-min` | `min-width: min-content;` |
| `.mn-wi-fit` | `min-width: fit-content;` |
| `.mn-wi-fill` | `min-width: fill-available;` |
| `.mn-wi-max-s` | `min-width: max-content;` |
| `.mn-wi-min-s` | `min-width: min-content;` |
| `.mn-wi-fit-s` | `min-width: fit-content;` |
| `.mn-wi-fill-s` | `min-width: fill-available;` |
| `.mn-wi-max-m` | `min-width: max-content;` |
| `.mn-wi-min-m` | `min-width: min-content;` |
| `.mn-wi-fit-m` | `min-width: fit-content;` |
| `.mn-wi-fill-m` | `min-width: fill-available;` |
| `.mn-wi-max-l` | `min-width: max-content;` |
| `.mn-wi-min-l` | `min-width: min-content;` |
| `.mn-wi-fit-l` | `min-width: fit-content;` |
| `.mn-wi-fill-l` | `min-width: fill-available;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.mn-wi-max-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/min-widths.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/min-widths.css` — formatted
- `dist/min-widths.min.css` — minified

## License

MIT
