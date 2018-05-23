# Sass-Starter Project
##### A Sass Boiler Plate project for starting any project with sass files structure already set up

## Sass Overview
### Variables
for relating component-specific values to others and preventing magic numbers
### Mixins
for dynamically generating variations of the component (not necessary if few variations exist)
### Structure
the CSS component layout/structure, excluding any non-layout rules, such as color
### Relationships
any component-specific CSS with regard to relationships (via combinators) with other components
### Themes
thematic CSS for non-layout component styling, such as background, colors, shadows, etc.
### Exported Selectors
the manifested CSS classes/selectors, if they are to be expose

## File Structure
* css
    * main_styles.css
* scss
    * base
        * _colors.scss
        * _resets.scss
        * _typography.scss
    * components
    * layout
         * _footer.scss
         * _headers.scss
         * _navigation.scss
    * pages
    * themes
    * utilities
         * _functions.scss
         * _mixins.scss
         * _variables.scss
    * vendors
    * main_styles.scss

## Resources
* A Great Resource to learn more about Sass: [Sass Guidelines](https://sass-guidelin.es/#naming-conventions).
* A Great Resource to learn some Tips and Tricks for Sass: [Sass Tips](https://scotch.io/tutorials/aesthetic-sass-1-architecture-and-style-organization).
* A Great Resource to learn more about how to set up Sass files: [Sass Files Structure](https://www.sitepoint.com/architecture-sass-project/).