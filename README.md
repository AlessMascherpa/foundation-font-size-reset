foundation-font-size-reset
==========================

Reset for a more accessible fonts in Zurb awesome Foundation front-end framework.

For a site to be accessible, among other things, it should allow users to resize the text by configuring the browser. See http://www.w3.org/WAI/changedesign

Foundation (http://foundation.zurb.com) has some accessibility issues with text (font) to be resized this way (https://github.com/zurb/foundation/issues/1222). Same problems that twitter bootstrap (https://github.com/twitter/bootstrap/issues/1943) has (or Github, but that is not an OS framework). The problem, in Foundation case, is relatively simple to avoid: just grab the foundation-font-reset.min.css from the stylesheets dir of this project and add it to your Foundation web page.

To test the project just copy its content to a downloaded Zurb Foundation project: http://foundation.zurb.com/download.php and open test.html in a browser. You can compare to the original css by opening the Foundation project index.html.

**NOTE:** This reset is for Foundation 3, Foundation 4 does not have this accesibility problem.
