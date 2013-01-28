Styleguide
==========

[Neo Columbus] CSS and HTML style guide

Generate CSS:

$`compass compile`




Topics to discuss
==========

* ## Media Queries
  * Retina
  * Responsive
  * **Jerry:** I've found waiting to the end to do these is wayyy more difficult and soul crushing.


* ## Class naming
  * Avoid IDs
  * Avoid element type in CSS? Ex: p.error, li.item
  * Aim for shallow nesting (or no nesting) of selectors

* ## Standardize on box model?
  * box-sizing: border-box;


* ## Standard control types?
  *  Buttons, popovers, forms, etc.

* ## How do we solve the stale CSS problem?
Too much crap gets left behind. Overrides from standard styles get messy and there is no standard place to put them.
_Generic components go in their own file. Page specific styles (and their overrides) go in their own file._
  * _button.css.sass
  * _popover.css.sass
  * _post_edit_page.css.sass
  * _post_new_page.css.sass

* ## Avoid writing unnecessary markup
  * More to maintain
  * harder to manipulate
  * Could be the source of some unused styles
