# DRY SCSS

## Partials

*Segmented scss files which contain various styling categories, which compile into one css file for rendering.*

```
Declared by using a '_' before the name of the scss file, eg.
    - _variables.scss
    - _base.scss
    - _layouts.scss
    - _mediaQueries.scss
```
```
Files are imported into the main.scss file using '@import'

*note that files are prioritised in the order they are requested in the '@import' declaration*
```