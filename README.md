
Personal CSS3 TextMate bundle
====================================
Simple CSS3 Bundle that includes some of the basic CSS3 properties I use on daily basis.

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
