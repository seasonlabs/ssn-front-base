# What

A base set of SCSS stylesheets to start projects. No frameworks or learning curve, just a set of empty files to be customised as you need and a couple of handy mixins and functions.

We work with plain HMTL, Ruby on Rails and PHP projects at [season](http://www.season.es), so we've been working on a (really) simple structure affordable for all scenarios that can be used as standalone or integrated with generators/compilers such as yeoman or compass.


## This thing at a glance

Directory         | Purpose
----------------- | ----------------------------------------------------------------------
`core`            | Core styles: variables, functions and mixins.
`base`            | Holding the collection of high-level parts.
`layout`          | Define the the relationship between base elements or components.
`components`      | Define the relationship between elements.
`elements`        | Lowest-level _repeatable_ elements.
`vendor`          | Vendor files, in case you need to add them here.


## Some examples

### Base

Place here the the header, site navigation or the site footer.

### Layout

Layout templates. How many page types are in the website? Here you would define sidebars, margins between regions and that stuff.

### Components

Use as an example an agenda teaser display. You would have some elements (date view, title, description and a call to action). Here you would build this teaser display.


### Elements

The lowest-level. Buttons, date displays, blockquotes...


# Credits

This codebase has been baked by [@season_es](https://github.com/seasonlabs) and is inspired by a bunch of lectures and conversations about structures.