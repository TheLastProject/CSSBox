# CSSBox
A simple, pure-CSS Lightbox replacement.

An example page is available in the gh-pages branch, or online on [GitHub Pages](https://thelastproject.github.io/CSSBox/).

## Why CSSBox?
* Absolutely no JavaScript
* Just over 1kb unminified (1445b including comments, 1139b excluding comments)
* There is an even smaller version without gallery functionality in the v1 branch
* Centers the image
* Adds a nice, realistic shadow to the image
* Dims the background
* Allows you to navigate through images
* Completely responsive, works on any screen size
* Has a pretty fade in and fade out animation

## Usage
Upload cssbox.css to your server and add a stylesheet link to it in your CSS.

Add your images like this:

    <div class="cssbox">
        <a id="image2" href="#image2"><img class="cssbox_thumb" src="image_thumb.jpeg" />
            <span class="cssbox_full"><img src="image_full.jpeg" /></span>
        </a>
        <a class="cssbox_close" href="#void"></a>
        <a class="cssbox_prev" href="#image1">&lt;</a>
        <a class="cssbox_next" href="#image3">&gt;</a>
    </div>

In the example above, you add an image with id image2 (make sure that appears
consistently in the a tag), with a close button, a previous button which
switches to image1 and a next button which switches to image3.

If you do not need the previous and next buttons, just leave the a elements
out. If you NEVER need gallery functionality, you may want to look in the v1
branch, which contains a smaller version without gallery functionality.

When a visitor clicks the tumbnail, the fullsize preview will appear in the
center of the screen and they can navigate through images.

Note: We use #void in the HTML to not jump to the top of the page when closing
the gallery. This is a hack, but should work as long as you don't have any div
with ID void on your page. If you do, choose another name.

## License
Creative Commons Attribution-ShareAlike 4.0

Credits do not need to be on your website, just leave them in the CSS.

