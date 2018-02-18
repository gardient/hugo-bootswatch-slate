# Hugo Bootswatch Slate

## Configuration

Added config properties with their defaults:

``` toml
[params]
# show brand
showbrand = true

# custom brand html code, defaults to page title
brand = 'page title'

# whether the top nav should be fixed
fixednav = false

# subtitle on the main page
subtitle = ''

# highlight.js
## highlight.js style (ex: 'vs2015')
highlightjs = ''
## highlight.js languages
highlightjs_extra_languages = []

# your custom javascript
custom_js = []

#your custom css
custom_css = []
```

## TODO

- [x] Set up base template
  - [x] Set top nav
    - [x] auto generate menu's from `main`
    - [x] configurable brand (can be hidden or custom, defaults to site title)
    - [x] top nav can be configured to be sticky
  - [x] css in top, js at the end of body
  - [x] default google analitycs template added to base
  - [x] added highlight.js
- [x] Set up homepage template
  - [x] Post summry template
- [ ] Complete readme
- [ ] Add list page template to post section
- [ ] Add taxonomy templates
