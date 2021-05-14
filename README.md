This is a starter scss kit for developing custom WordPress themes.

## Directory Structure

- `config.scss` Adjust variables for colors, font families, global values, and breakpoints
- `style.scss` @import all SCSS files here

### Base
This code should change very little from project to project. Ideally, this is touched at the beginning of the project and never opened again.

- `components/` Adjust typography, buttons, forms, the scrollbar, or anything that would be at the top of the cascade
- `atomic.scss` Utility classes
- `mixins.scss`
- `normalize.scss`

### Project Components
These elements are project-specific.

- `gutenberg-blocks` I'd recommend using the Lazy Blocks plugin ;)
- `template-parts`
- `footer.scss`
- `global.scss` A bin for odd, shared classes and styles that don't belong anywhere else
- `header.scss`

### Templates
Any templates created in the WordPress theme can be styled here.
