
My Experimental CSS3 TextMate bundle
====================================

CSS3.tmbundle is a set of CSS3 properties that are either prefixed with vendor strings or use browser-specific properties to achieve a similar effect (ie. `filter` on IE).

What's already available
------------------------

Not much :-)

- **Gradients**: Firefox, Safari, Chrome, Internet Explorer (no stops)
  - `gradx`+`tab` - Horizontal Gradient
  - `grady`+`tab` - Vertical Gradient

Installing
----------

    cd ~/Library/Application\ Support/TextMate/Bundles

Clone the repo

    git clone git://github.com/oskarkrawczyk/css3-tmbundle.git CSS3.tmbundle

Reload Bundles

    osascript -e 'tell app "TextMate" to reload bundles'
