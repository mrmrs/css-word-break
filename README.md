# css-word-break

Functional CSS for word-break

## Filesize

| File | Size |
|------|------|
| `dist/word-break.css` | 1753 bytes |
| `dist/word-break.min.css` | 1253 bytes (264 Gzipped) |

## Install

```sh
npm install css-word-break
```

## Usage

### Import

```css
@import "css-word-break";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-word-break/dist/word-break.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-word-break/dist/word-break.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.wb-normal` | `word-break: normal;` |
| `.wb-ba` | `word-break: break-all;` |
| `.wb-ka` | `word-break: keep-all;` |
| `.wb-auto` | `word-break: auto-phrase;` |
| `.wb-inherit` | `word-break: inherit;` |
| `.wb-initial` | `word-break: initial;` |
| `.wb-revert` | `word-break: revert;` |
| `.wb-revert-layer` | `word-break: revert-layer;` |
| `.wb-unset` | `word-break: unset;` |
| `.wb-normal-s` | `word-break: normal;` |
| `.wb-ba-s` | `word-break: break-all;` |
| `.wb-ka-s` | `word-break: keep-all;` |
| `.wb-auto-s` | `word-break: auto-phrase;` |
| `.wb-inherit-s` | `word-break: inherit;` |
| `.wb-initial-s` | `word-break: initial;` |
| `.wb-revert-s` | `word-break: revert;` |
| `.wb-revert-layer-s` | `word-break: revert-layer;` |
| `.wb-unset-s` | `word-break: unset;` |
| `.wb-normal-m` | `word-break: normal;` |
| `.wb-ba-m` | `word-break: break-all;` |
| `.wb-ka-m` | `word-break: keep-all;` |
| `.wb-auto-m` | `word-break: auto-phrase;` |
| `.wb-inherit-m` | `word-break: inherit;` |
| `.wb-initial-m` | `word-break: initial;` |
| `.wb-revert-m` | `word-break: revert;` |
| `.wb-revert-layer-m` | `word-break: revert-layer;` |
| `.wb-unset-m` | `word-break: unset;` |
| `.wb-normal-l` | `word-break: normal;` |
| `.wb-ba-l` | `word-break: break-all;` |
| `.wb-ka-l` | `word-break: keep-all;` |
| `.wb-auto-l` | `word-break: auto-phrase;` |
| `.wb-inherit-l` | `word-break: inherit;` |
| `.wb-initial-l` | `word-break: initial;` |
| `.wb-revert-l` | `word-break: revert;` |
| `.wb-revert-layer-l` | `word-break: revert-layer;` |
| `.wb-unset-l` | `word-break: unset;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.wb-normal-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/word-break.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/word-break.css` — formatted
- `dist/word-break.min.css` — minified

## License

MIT
