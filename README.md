# [Build a Tribute Page](https://www.freecodecamp.com/challenges/build-a-tribute-page)

Part of the [freecodecamp](https://www.freecodecamp.com) curriculum.

## Objective

Build a CodePen.io app that is functionally similar to this: https://codepen.io/FreeCodeCamp/full/NNvBQW/.

1. User Story: I can view a tribute page with an image and text.
2. User Story: I can click on a link that will take me to an external website with further information on the topic.

## Solution

* Built using [Sass](http://sass-lang.com/) and [Normalize.css](https://necolas.github.io/normalize.css/).
* This solution is built for mobile first and will display correctly across all browser sizes.
* The tribute page is built in the form of a timeline detaling the life of Patrick Leigh Fermor.
* Notable events during his life are shown, alongside details of his published works.
* The timeline is implemented using CSS and Sass.
* Using a ::before psuedo class, a line is drawn to the left of the list.
* Circles are added to the line at each event. They are drawn using a border radius of 50%.

## Development tools

The following tools were used in development:

* Yarn / npm scripts in package.json.
* [node-sass](https://github.com/sass/node-sass) to compile Sass files to CSS.
* [browser-sync](https://github.com/Browsersync/browser-sync) to push CSS changes to the browser.
* [onchange](https://github.com/Qard/onchange) to implement watch functionality.
* [npm-run-all](https://github.com/mysticatea/npm-run-all) to run a series of Yarn / npm background scripts in parallel.

Inspiration taken from [Why npm Scripts?](https://css-tricks.com/why-npm-scripts/) on [CSS-Tricks](https://css-tricks.com).
