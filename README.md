<img alt="Brisky CSS Logo" src="https://raw.githubusercontent.com/crical-media/brisky-css/main/brisky-logo.jpg">

# Brisky CSS Framework

Brisky is a simple, lightweight and fast CSS framework inspired by Tailwind CSS utility classes and Bootstrap.

## Usage with npm

```sh
npm install brisky-css
```

## Usage with CDN

```html
<link href="https://unpkg.com/brisky-css/dist/brisky-css-variables.css"	rel="stylesheet"/>
<link href="https://unpkg.com/brisky-css/dist/brisky-css.min.css" rel="stylesheet"/>
```

## Import

Minified CSS:

```css
@import "brisky-css/dist/brisky-css-variables.css";
@import "brisky-css/dist/brisky-css.css";
```

Full SCSS:

```css
@import "brisky-css/src/main.scss";
```

## SCSS Variables

```scss
$cm-primary: #0ff38f;
$cm-secondary: #6c757d;
$cm-success: #198754;
$cm-info: #0dcaf0;
$cm-warning: #ffc107;
$cm-danger: #dc3545;
$cm-light: #ffffff;
$cm-dark: #06111e;

$cm-body-color: #06111e;
$cm-body-bg: #ffffff;

$cm-body-font-family: "Roboto", sans-serif;
$cm-body-font-size: 1rem;
$cm-body-font-weight: 400;
$cm-body-line-height: 1.5;

$cm-heading-font-weight: 700;
$cm-heading-line-height: 1.2;

$cm-breakpoint-xs: 576px;
$cm-breakpoint-sm: 768px;
$cm-breakpoint-md: 992px;
$cm-breakpoint-lg: 1200px;
$cm-breakpoint-xl: 1600px;
```

## Normalize

We are using normalize.css v8.0.1 | MIT License | [github.com/necolas/normalize.css](https://github.com/necolas/normalize.css)

## License

[MIT](https://github.com/crical-media/brisky-css/blob/main/README.md)

## Copyright

Copyright 2023, crical.media
