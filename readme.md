This is my own attempt at creating a template for my web development. So far I'm just working with HTML and CSS and just getting started a little with JS. I'm doing my CSS in SASS and my HTML in HAML so I've got those files in place. I'm assuming that when I set up the project in my preprocessor I'll tell it where to put the styles.css and index.haml files so as of right now I don't have any of those config files in place. 

// Here's the overall structure to this base styles template:
scss/
|
|-- modules/              # Common modules
|   |-- _all.scss         # Include to get all modules
|      |-- _utility.scss  # Module name
|      |-- _colors.scss   # Etc...
|   ...
|
|-- partials/             # Partials
|   |-- _base.sass        # imports for all mixins + global project variables
|   |-- _buttons.scss     # buttons
|   |-- _figures.scss     # figures
|   |-- _grids.scss       # grids
|   |-- _typography.scss  # typography
|   |-- _reset.scss       # reset
|   ...
|
|-- vendor/               # CSS or Sass from other projects
|   |-- _colorpicker.scss
|   |-- _jquery.ui.core.scss
|   ...
|
`-- main.scss            # primary Sass file

Adapted from http://thesassway.com/beginner/how-to-structure-a-sass-project
