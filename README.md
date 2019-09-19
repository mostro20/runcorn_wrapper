# runcorn_wrapper

Based on https://github.com/qld-gov-au/web-template-release/

Written to provide some wrapper elements (header and footer) to make the AS QSA instance appear "government-y" as well as some styles and components to reuse for elements inside the forms.

## theme

This is all based on Bootstrap v4.1, and you can compile from the `SCSS folder` to create a theme. Place all your favourite overrides in the `scss/overrides.scss` file.

## template html

This contains three template HTML files:
 * `content-page.html`, which is a responsive three column layout,
 * `content-page-left.html`, which contains a left column only,
 * `content-page-right.html`, which contains a right column only,
 * `component-guide.html`, which contains a individual reusable components,
 * `content-page-cart.html`, contains the 3-col layout with a sample Q-Gov shopping cart.

All three will reference the assets as a theme, but you can overrides this with what you develop from the Bootstrap SCSS folder.

## as inspired templates

The following pages have been developed to show some ways of using components to return AS pages:
 * `result-sample.html`, sample layout for Agencies
 * `result-sample-series.html`, sample layout for Series
 * `result-sample-record.html`, sample layout for items
 * `result-sample-function.html`, sample layout for functions
 * `result-sample-mandate.html`, sample layout for mandates

## search templates

The following pages have been developed to show search pages and results:
 * `search-page.html`, search with advanced Search
 * `search-results.html`, TODO - search results

## account pages

This provides templates for the account pages
 * `my-account.html`, TODO

## admin pages

This provides templates for the admin functionality
 * `system-admin.html`, TODO
