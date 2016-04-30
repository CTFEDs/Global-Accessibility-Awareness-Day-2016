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

## Two lightning talks

* what topics?
* one on theory, one on practical?

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

## Examples to work through

* Heydon Pickering's [practical ARIA examples](http://heydonworks.com/practical_aria_examples/)
* Font Awesome 4.6 Released: [Making accessibility more accessible](https://articles.fortawesome.com/font-awesome-4-6-released-d7213342698a#.j8om7wij4)
* [Code Library (Beta) from Deque University](https://dequeuniversity.com/library/)

## Tools

* pa11y
* tenon
* bbc-a11y
* check my pinboard bookmarks

# Other people's stuff

* How to convice your boss. Handout?
* Activity list. Handout?
* Follow-ups: blog post, tweets, share on meetup, Slacks.
