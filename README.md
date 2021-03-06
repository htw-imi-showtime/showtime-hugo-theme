# Showtime Hugo Theme
The Hugo theme used for the showtime website

## Structure

### `archetypes/`
Contains templates for generating new pages using the Hugo CLI.

### `layouts/`
The layouts folder contains the HTML templates for this theme.
* `index.html` - Contains the home page's layout
* `_default/`
  * `baseof.html` - Contains the base structure of the site which should be always applied
  * `list.html` - Contains the layout for the index pages of the different sections (e.g. ss20, ...)
  * `project.html` - Contains the layout for the project pages
  * `single.html` - Contains the layout for all single pages, like the imprint
* `partials/` - Contains partial templates to be included/reused in other templates for this theme
* `shortcodes/` - Contains partials which can be included in markdown pages

### `static/`
The static folder contains files that should be served without being processed by Hugo. You may put assets like images, stylesheets or scripts into this folder.

### `theme.toml`
Contains metadata about the theme (e.g. theme name, author, description)
