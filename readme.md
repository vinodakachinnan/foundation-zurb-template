![http://ltdocs.info/](src/assets/img/Logo.png?row=true)

# Living Traditions

A web interface project for [India Foundation for the Arts](http://www.indiaifa.org/) & [Asia Art Archive](http://www.aaa.org.hk/) Archival Fellowship. 2015-2016

[![devDependency Status](https://david-dm.org/zurb/foundation-zurb-template/dev-status.svg)](https://david-dm.org/zurb/foundation-zurb-template#info=devDependencies)

### Detaild [DOCUMENTAION](http://ltdocs.info/) of the project.

Interface is built on top of official ZURB Template for use with [Foundation for Sites](http://foundation.zurb.com/sites). It has a Gulp-powered build system with these features:

- Handlebars HTML templates with Panini
- Sass compilation and prefixing
- JavaScript concatenation
- Built-in BrowserSync server
- Velocity js for animation
- Jquery-Colorbox for lightbox
- CountTo for landing page animation
- For production builds:
  - CSS compression
  - JavaScript compression
  - Image compression

## Prerequisites

To use this template, your computer needs:

- [NodeJS](https://nodejs.org/en/) (0.12 or greater)
- [Git](https://git-scm.com/)

## Installation

Download it with Git:

```bash
git clone https://github.com/vinodakachinnan/living-traditions.git
```

Then open the folder in your command line, and install the needed dependencies:

```bash
cd living-traditions
npm install
bower install
```

Finally, run `npm start` to run Gulp. Your finished site will be created in a folder called `dist`, viewable at this URL:

```
http://localhost:8000
```

To create compressed, production-ready assets, run `npm run build`.

## Files

```txt
├───assets
│   ├───img
│   │   │   .gitkeep
│   │   │   Logo.png
│   │   │   Logo.svg
│   │   │
│   │   ├───about
│   │   ├───genre
│   │   ├───interchange
│   │   ├───jyoti-bhatt
│   │   ├───landing
│   │   ├───nav
│   │   ├───place
│   │   └───year
│   ├───js
│   │       app.js
│   │
│   └───scss
│       │   app.scss
│       │   _colorbox.scss
│       │   _custom.scss
│       │   _queries.scss
│       │   _settings.scss
│       │
│       └───components
│               .gitkeep
│
├───data
│       .gitkeep
│       about.json
│       genre.json
│       info.json
│       nav.json
│       year.json
│
├───layouts
│       default.html
│
├───pages
│       about.html
│       genre.html
│       index.html
│       nav.html
│       place.html
│       year.html
│
├───partials
│       .gitkeep
│       about-partial.html
│       info-partial.html
│       jyoti-bhatt-partial.html
│
└───styleguide
        index.md
        template.html
```

## Built with

* [Foundation 6](http://foundation.zurb.com/)
* [Velocity js](http://velocityjs.org/)
* [Colorbox](http://www.jacklmoore.com/colorbox/)
* [CountTo](https://github.com/mhuggins/jquery-countTo)

## Credits

* Sabih Ahmed
* Sneha Ragavan
* Rashmimala

Interface and the documentation is made by [Vinod Velayudhan](vinodaschinnan@gmail.com).