# Introduction

Ideas for warm-up questions.

* What do you already know about accessibility?
* Who does accessibility help?
* Is accessibility easy or hard?
* When is the best time to consider accessibility in a project?
* Who will you share the stuff from the workshop with? (tie this in to SMART goal at end)
* Who do you know that would benefit from web sites being more accessible?
* What accessiblity features would you benefit from?

Other start-up activity ideas.

* When might accessibility features be useful to a person? (e.g. injury, dark room. Have examples ready for them to pick from?)
* introduce some [personas](http://rosenfeldmedia.com/a-web-for-everyone/personas-for-accessible-ux/)?

## Activities

* Need to highlight that the barrier part of accessibility means other things like language, environment. Get attendess to make this list. Use personas as jumping off point / helper? In intro lightning talk?

## Two lightning talks (2 x 5m)

* what topics?
* one on theory, one on practical?

### Tour the personas (10m)

* Walk around, talk notes.
* Pick one or two to focus on?

### Find things to improve in your stuff (15m)

* Grab a copy of the GAAD activites handout.
* As a table, split up the activities between yourselves. Make sure that you cover all of them.
* Discuss and write down ways to get others at the office to do these on WGAAD.
  * What's the value?
  * Who does it affect?

### Make a checklist (30m)

* Grab two different colour pens: one for FED and one for UX.
* Go through A Web For Everyone's [APPENDIX A: Accessible UX Principles and Guidelines](handout/AWFE-AppendixA1.pdf).  Mark with a tick items that are FED and items that are UX-related.
* Pick the four most important items write them down on sticky notes. Pick three for FED and one for UX.
* As a table, write down some ideas for how to make these things happen. It could be a tool or a process change.

## Examples to work through (30m)

* Heydon Pickering's [practical ARIA examples](http://heydonworks.com/practical_aria_examples/)
* Font Awesome 4.6 Released: [Making accessibility more accessible](https://articles.fortawesome.com/font-awesome-4-6-released-d7213342698a#.j8om7wij4)
* [Code Library (Beta) from Deque University](https://dequeuniversity.com/library/)
* [Simply Accessible examples](http://examples.simplyaccessible.com/)

# Your stuff

## Checklist

### Primary

* [Validate](http://validator.w3.org/) your HTML.
* Use HTML5 elements like `section`, `article`, `header`, `footer`, and `nav`.* Make sure every image has `alt` text.
* Use the `picture` element and `srcset` to provide the image most suitable for the user's device. You can use [Picturefill](http://scottjehl.github.io/picturefill/) to enable support for `picture` in browsers that don't support it yet.
* Think about performance: what are you loading that people won't see?

### Secondary

* Use HTML5 input types like `search`, `email`, and `date`.
* Don't use inline CSS (using the `style` tag or `style` attribute on HTML elements): use external stylesheets (using the `link` tag). The exception is for [critical CSS](https://developers.google.com/speed/docs/insights/PrioritizeVisibleContent#RemoveUnusedCSS): initially sending a small amount of CSS in the head of the document so that page rendering starts as early as possible.
* Don't use inline JS (using a `script` tag or directly on an HTML element): include external JS files (using the `src` attribute on a `script` element).
* Place `script` elements at the bottom of the page, or load them asynchronously by adding the `async` attribute to the `script` tag (this means that the loading of the JavaScript files won't block loading of the page).

## Tools

* [pa11y](http://pa11y.org/)
* [a11y](https://addyosmani.com/a11y/)
* [tenon](https://tenon.io/)
* [axe](http://www.deque.com/products/axe/)
* [The A11y Machine](https://github.com/liip/TheA11yMachine)
* [BBC Accessibility Standards Checker](https://github.com/bbc/bbc-a11y)
* [tota11y](http://khan.github.io/tota11y/), an accessibility visualization toolkit
* Web Aim's [Web Accessibility Evaluation Tool](http://wave.webaim.org/)
* Big list on [Paciello Group](https://www.paciellogroup.com/blog/2014/10/accessibility-testing-tools-updated/)
* [Lea Verou's colour contrast ratio checker](http://leaverou.github.io/contrast-ratio/)

# Other people's stuff

* How to convince your boss. Handout?
* Activity list. Handout?
* Follow-ups: blog post, tweets, share on meetup, Slacks.
