## CSSBox
A simple, pure-CSS Lightbox replacement.

## Why CSSBox?
* Actually lightweight (844b including comments, 548b excluding comments, unminified!)
* Centers the image
* Adds a nice, realistic shadow to the image
* Dims the background
* Completely responsive, works on any screen size
* Has a pretty fade in animation

## Usage
Upload cssbox.css to your server and add a stylesheet link to it in your CSS.

Add your images like this:

    <img class="cssbox_thumb" tabindex=1 src="image_thumbnail.png" /><span class="cssbox_full"><img src="image_full.png" /></span>

When a visitor clicks the tumbnail, the fullsize preview will appear in the
center of the screen.

## Example
An example page is available in the gh-pages branch, or online on [GitHub Pages](https://thelastproject.github.io/CSSBox/).

## License
Creative Commons Zero 1.0

