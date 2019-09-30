# Runcorn Wrapper

Based on https://github.com/qld-gov-au/web-template-release/

Written to provide some wrapper elements (header and footer) to make the AS QSA instance appear "government-y" as well as some styles and components to reuse for elements inside the forms.

## Theme

This is all based on Bootstrap v4.1, and you can compile from the `SCSS folder` to create a theme. Place all your favourite overrides in the `scss/overrides.scss` file.

## Generic Template html files

This contains three template HTML files, as well as a component guide and an example file for embedded the shopping:
 * `content-page.html`, which is a responsive three column layout,
 * `content-page-left.html`, which contains a left column only,
 * `content-page-right.html`, which contains a right column only,
 * `component-guide.html`, which contains a individual reusable components,
 * `content-page-cart.html`, contains the 3-col layout with a sample Q-Gov shopping cart.

All files will reference the assets as a theme, but you can overrides this with what you develop from the Bootstrap SCSS folder.

## ArchiveSpace - Search templates

The following pages have been developed to show an advanced search pages and a results page:
 * `search-page.html`, search with advanced Search
 * `search-results.html`, search results results page

## ArchivesSpace - Content types templates

The following pages have been developed to show some ways of using components to return AS content pages (Agency, Series, Items, Functions, Mandates):

 * `result-sample.html`, sample layout for Agencies
 * `result-sample-series.html`, sample layout for Series
 * `result-sample-record.html`, sample layout for items
 * `result-sample-function.html`, sample layout for functions
 * `result-sample-mandate.html`, sample layout for mandates
 * `result-records-wt-actions-open.html`, layout of a record with actions for open (add to cart etc.)
 * `result-records-wt-actions-closed.html`, layout of a record with actions for closed (add to cart etc.)

 ## Administration pages

 This provides templates for the admin functionality
  * `system-login.html`, login page for admins
  * `system-admin.html`, overview / success screen from login
  * `system-requests-overview.html`, overview of all Reading Room results
  * `system-requests-results.html`, view of a specific Reading Room request result with printing picking slips
  * `system-users-overview.html`, overview of all users in the system
  * `system-users-results.html`, view of an individual user
  * `system-ordering`, TODO - ordering on behalf of users

## User account pages

This provides templates for the account pages, so when members of the public
 * `my-account-login.html`, - page for logging in for public users
 * `my-account-registration.html`, - page for users to register a new account
 * `my-account-profile.html`, - page for users to view their won profile details and update their information
 * `my-account-order-history.html`, - page where public users can access their order history
 * `my-account-order-history-results.html`, - page where public users view a specific request, which shows as a picking slip template
 * `my-account-ordering.html`, - page that logged in users can access to create orders and requests, works as the order cart
 * `my-account-order-closed.html`, request to view restricted access with web form
 * `my-account-saved-searches.html`, TODO - page where users can access their saved searches
 * `my-account-notifications.html` TODO - notifications page
 * `my-account-forgot-password.html` - forgot password password page
