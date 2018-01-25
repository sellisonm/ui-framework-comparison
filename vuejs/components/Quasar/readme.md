# Component - Quasar Framework

## Description
Build responsive websites, PWAs, hybrid mobile Apps (that look native!) and Electron apps, all simultaneously using same codebase, powered with Vue.

## Source
https://github.com/quasarframework/quasar

## Website
http://quasar-framework.org/

## License
MIT

## Getting Started
### Install CLI
npm install -g quasar-cli

## Things I LOVE
 - While dev webserver is running, real time building on save of a file and on error, browser immediatley shows error message along with code snippet.  Much better than ExtJS where you have to run the app and then get an obscure error to find you missed a requires.


## Built-in Web Server for dev
While developing with Dev Server ($ quasar dev):

Webbpack + vue-loader for single file Vue components
State preserving hot-reload
State preserving compilation error overlay
Lint-on-save with ESLint
Source maps

## Built-in during Production build
Javascript minified with UglifyJS
HTML minified with html-minifier
CSS across all components extracted into a single file and minified with cssnano
All static assets are compiled with version hashes for efficient long-term caching, and a production index.html is auto-generated with proper URLs to these generated assets.

## Things I LOVE


## Considerations
### Do the identified libraries have official support or are they community built? 
Community


### What does *state management* look like? 


### What does *routing* look like? 
*TODO* - Learn what this means http://quasar-framework.org/components/layout.html#Routing

### What does *data management (model/store)* look like? 


### Are there charting library wrappers available? For which libraries? 
None that I was able to find


### What table or grid libraries are available? Do they scale infinitely? 
Built-in DataTable that supports the following functionality
- Responsive (changes design when width is smaller than 600px to best accommodate small screens)
- Sticky columns
- Sticky headers
- Filter (by all columns or by one column)
- Sorting by columns
- Cell formatter methods
- Cell component renderer (through Vue scoped slots)
- Pagination
- Columns picker
- Row selection (single or multiple)
- Refresh functionality