# Prerequisites
* yarn package manager

# Getting Started
* `yarn install` - install dependencies with 
* `yarn dev` - run development localhost server
* `yarn build` - build prod files
* `yarn deploy` - deploy to gh-pages
* Windows users might need to run `yarn start` prior `yarn dev` to generate an initial build to avoid the `Cannot GET /` error when trying to initiate local browsersync.

# Generic Parcel Template
* Uses Sass and the 7-1 Pattern by Hugo Giraudel.
* Uses the JavaScript Revealing Module Pattern.
* Disables responsiveness on IE9 and below.
* Shows unobtrusive bar to the visitors who is visiting your website with an IE <= 9 browser.
* Prevents auto zoom on iOS when entering an input field.
* Disables auto-formatting of possible phone numbers in a webpage in Safari on iOS.
* Removes webkit input fields outline glow on focus.
* Added breakpoint mixins for more granular control.
* Added keyframes, animation, transition and transform mixins to boil down to just a few lines of code.
* Uses Parcel to bundle, minify, and optimize HTML, CSS and JS.

# Changelog
* 1.0.0
  * initial commit