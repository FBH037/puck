## npm
* modules: the gems of node
* `npm intsall`
* `npm install <package-name> --save`
* `npm install <package-name> -g`

## Sass

### Get Setup
1. Navigate to the root of the puck repo and run `npm install`.
1. Run `npm run watch`

* Compiles to CSS
* Varibales
* Partials
* Don't nest
* Mixins

Read about the [Sass Basics](http://sass-lang.com/guide)

## Make a Website

Quick demo.

Process:
1. Start prototyping in app.scss and create partials as you identify
patterns. You will almost always have a colors, layout, reset, and type
partial.
1. Drop in a reset stylesheet
1. Pick two fonts and include type-scale styles
1. Start bulding in black and white.
1. Make progress on the layout, then include some color from a color
palette.

### Resources:
* [CSS Reset](http://meyerweb.com/eric/tools/css/reset/)
* [Color Palette](http://app.coolors.co/)
* [Fonts That Don't
* [Type Scale](http://type-scale.com/)
Suck](http://somadesign.ca/demos/better-google-fonts/)

### Designed website

Starting with the Puck repo, make a good looking, one page website for a
new startup called Happycult.

Constraints:

* Your Sass should use a `colors` partial.
* Your Sass should use a `reset` partial.
* Your Sass should use a `type` partial.
* The homepage should have an about section.
* Use Lorem Ipsum for any site content.

## Grids

* Flexible Layout with [the RWD
formula](http://resources.sameerast.com/responsive-web-design-formula-easy-calculator.html)
* Floats and clearfix
* CSS box model
* Container class vs modifier class

Clone the [css-grids repo](https://github.com/gSchool/css-grid) and follow the instructions there.

### Class based grids

# Puck
Very small template for very small apps.

Template inclues:
____
* ES6 transpiling via Bable
* Sass
* Live reloading for Chrome
* Simple HTTP server

## Style
* Add custom CSS to `src/sass/`

## Scripts
* Add custom JavaScript in `src/js/`

Everything is compiled into the `dist` directory.

## Server
1. In the terminal, `cd` into the puck directory
1. Run `npm run watch` to start a server and build assets.
1. Visit localhost:8000 to see it in action.

## Live Reloading

Install the [Chrome extension](https://chrome.google.com/webstore/detail/livereload/jnihajbhpnppcggbcgedagnkighmdlei/related). This will connect to the default port that the `node-livereload` module expects.

> If we shadows have offended,  
> Think but this, and all is mended,  
> That you have but slumber'd here  
> While these visions did appear.  
> And this weak and idle theme,  
> No more yielding but a dream,  
> Gentles, do not reprehend:  
> If you pardon, we will mend:  
> And, as I am an honest Puck,  
> If we have unearned luck  
> Now to 'scape the serpent's tongue,  
> We will make amends ere long;  
> Else the Puck a liar call;  
> So, good night unto you all.  
> Give me your hands, if we be friends,  
> And Robin shall restore amends.  
