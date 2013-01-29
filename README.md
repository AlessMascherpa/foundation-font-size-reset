foundation-font-size-reset
==========================

Reset for a more accessible fonts in Zurb awesome Foundation front-end framework.

For a site to be accessible, among other things, it should allow users to resize the text by configuring the browser. See http://www.w3.org/WAI/changedesign

Foundation (http://foundation.zurb.com) has some accessibility issues with text (font) to be resized this way (https://github.com/zurb/foundation/issues/1222). Same problems that twitter bootstrap (https://github.com/twitter/bootstrap/issues/1943) has (or Github, but that is not an OS framework). But in the case of foundation is relatively simple to avoid: 
Just grab the foundation-font-reset.min.css from the stylesheets dir of this project and add it to your Foundation web page.

It seems by reading https://github.com/zurb/foundation/issues/1222#issuecomment-11064001 that Zurb Foundation maintainers will take this in consideration for the next version (the 4th). In the meantime... enjoy.
