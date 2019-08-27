# runcorn_wrapper

Based on https://github.com/qld-gov-au/web-template-release/

Written to provide some wrapper elements (header and footer) to make the AS QSA instance appear "goverment-y" as well as some styles and components to reuse for elements inside the forms.

## theme

This is all based on Bootstrap v3, and you can compile from the `SCSS folder` to create a theme. Place all your favourite overrides in the `scss/overrides.scss` file.

## template html

This contains three template HTML files:
`content-page.html`, which is a responsive three column layout,
`content-page-left.html`, which contains a left column only,
`content-page-right.html`, which contains a right column only.

All three will reference the assets as a theme, but you can overrides this with what you develop from the Bootstrap SCSS folder.
