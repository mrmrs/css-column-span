# css-column-span

Functional CSS for column-span

## Filesize

| File | Size |
|------|------|
| `dist/column-span.css` | 605 bytes |
| `dist/column-span.min.css` | 429 bytes (147 Gzipped) |

## Install

```sh
npm install css-column-span
```

## Usage

### Import

```css
@import "css-column-span";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-column-span/dist/column-span.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-column-span/dist/column-span.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.cs-non` | `column-span: none;` |
| `.cs-all` | `column-span: all;` |
| `.cs-span` | `column-span: inherit;` |
| `.cs-non-s` | `column-span: none;` |
| `.cs-all-s` | `column-span: all;` |
| `.cs-span-s` | `column-span: inherit;` |
| `.cs-non-m` | `column-span: none;` |
| `.cs-all-m` | `column-span: all;` |
| `.cs-span-m` | `column-span: inherit;` |
| `.cs-non-l` | `column-span: none;` |
| `.cs-all-l` | `column-span: all;` |
| `.cs-span-l` | `column-span: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.cs-non-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/column-span.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/column-span.css` — formatted
- `dist/column-span.min.css` — minified

## License

MIT
