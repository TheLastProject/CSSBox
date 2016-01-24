## CSSBox
A simple, pure-CSS Lightbox replacement.

## Why CSSBox?
* Just over 1kb unminified (1284b including comments, 1084b excluding comments)
* There is an even smaller version without gallery functionality in the v1 branch
* Centers the image
* Adds a nice, realistic shadow to the image
* Dims the background
* Allows you to navigate through images
* Completely responsive, works on any screen size
* Has a pretty fade in animation

## Usage
Upload cssbox.css to your server and add a stylesheet link to it in your CSS.

Add your images like this:

    <a id="image2" href="#image2"><img class="cssbox_thumb" src="image_thumb.jpeg" height="300" width="300" />
        <span class="cssbox_full"><img src="image_thumb.jpeg" /></span>
    </a>
    <a class="cssbox_close" href="#"></a>
    <a class="cssbox_prev" href="#image1">&lt;</a>
    <a class="cssbox_next" href="#image3">&gt;</a>

In the example above, you add an image with id image2 (make sure that appears
consistently in the a tag), with a close button, a previous button which
switches to image1 and a next button which switches to image3.

If you do not need the previous and next buttons, just leave the a elements
out. If you NEVER need gallery functionality, you may want to look in the v1
branch, which contains a smaller version without gallery functionality.

When a visitor clicks the tumbnail, the fullsize preview will appear in the
center of the screen and they can navigate through images.

## Example
An example page is available in the gh-pages branch, or online on [GitHub Pages](https://thelastproject.github.io/CSSBox/).

## License
Creative Commons Attribution-ShareAlike 4.0

