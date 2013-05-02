StartBox SASS Child theme
============
The default StartBox child theme with Sass!
-----------------------------------

This is a starter child theme for [StartBox](http://wordpress.org/extend/themes/responsive) WordPress theme framework that uses SASS/SCSS for editing the style.

- Styles are separated into categorical files (and compiled to one stylesheet).
- Separate files for both variables and mixins/functions. Change the entire look of the theme simply by adjusting these variables!
- Comes with a config.rb file. Defaults to outputting a compressed stylesheet.

Installation
------------

*Important:* You'll need the [StartBox](http://wordpress.org/extend/themes/responsive) WordPress theme framework. Please follow the installation instructions there.

This child theme will go in your themes directory adjacent to StartBox.

Usage
------------

To edit the theme, you'll need compass and sass running. You can install it with a terminal command:
	sudo gem install compass

For more about sass:
- [sass-lang.com](http://sass-lang.com/).
- [thesassway.com](http://thesassway.com/).
- [alistapart.com/article/getting-started-with-sass](http://alistapart.com/article/getting-started-with-sass).

All SASS files are in the 'SASS' directory and you can edit any one you like. `style.scss` is the main stylesheet, and you can see it importing the other sass files near the top. These are not traditional css imports as they will all be imported and compiled together to create your theme's style.css. Your browser will be using `style.css` as usual.