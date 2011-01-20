
Personal CSS3 TextMate bundle
====================================
This bundle was cloned from Oskar Krawczyk (http://nouincolor.com).

I removed the gradient prefixes for IE (whenever you use ms-filter God kills a platypus) and added some new properties that I use on daily basis, which are described below.

What's already available
------------------------

- **Gradients**: Firefox, Safari, Chrome
  - `gradx`+`tab` - Horizontal Gradient
  - `grady`+`tab` - Vertical Gradient
 
- **Box Shadow**: Firefox, Safari, Chrome, Opera
  - `bs` + `tab`
  
- **Border radius**: Firefox, Safari, Chrome, Opera
  - `br-full` + `tab` - Full border radius declaration, separate for every corner.
  - `br-simple` + `tab` - Simplified declaration - one value used for every corner.
  - `br-tl` + `tab` - Border radius for top-left corner.
  - `br-tr` + `tab` - Border radius for top-right corner.
  - `br-br` + `tab` - Border radius for bottom-right corner;
  - `br-bl` + `tab` - Border radius for bottom-left corner;  

Installing
----------

    cd ~/Library/Application\ Support/TextMate/Bundles

Clone the repo

    git clone git://github.com/andrzejkala/css3-tmbundle.git CSS3.tmbundle

Reload Bundles

    osascript -e 'tell app "TextMate" to reload bundles'
