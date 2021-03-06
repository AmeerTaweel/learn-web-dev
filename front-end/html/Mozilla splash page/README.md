# Assessment: Mozilla splash page

This assessment is part of [HTML — Structuring the Web course](https://developer.mozilla.org/en-US/docs/Learn/HTML) by [MDN Web Docs](https://developer.mozilla.org/).

## Project brief

In this assessment we are presenting you with a mostly-finished Mozilla splash page, which aims to say something nice and interesting about what Mozilla stands for, and provide some links to further resources. Unfortunately, no images or video have been added yet — this is your job! You need to add some media to make the page look nice and make more sense. The following subsections detail what you need to do:

### Preparing images

Using your favourite image editor, create 400px wide and 120px wide versions of:

* `firefox_logo-only_RGB.png`
* `firefox-addons.jpg`
* `mozilla-dinosaur-head.png`

Call them something sensible, e.g. `firefoxlogo400.png` and `firefoxlogo120.png`.

Along with `mdn.svg`, these images will be your icons to link to further resources, inside the `further-info` area. You'll also link to the firefox logo in the site header. Save copies of all these inside the same directory as `index.html`.

Next, create a 1200px wide landscape version of `red-panda.jpg`, and a 600px wide portrait version that shows the panda in more of a close up shot. Again, call them something sensible so you can easily identify them. Save a copy of both of these inside the same directory as `index.html`.

### Adding a logo to the header

Inside the `<header>` element, add an `<img>` element that will embed the small version of the Firefox logo in the header.

### Adding a video to the main article content

Just inside the `<article>` element (right below the opening tag), embed the YouTube video found at `https://www.youtube.com/watch?v=ojcNcvb1olg`, using the appropriate YouTube tools to generate the code. The video should be 400px wide.

### Adding responsive images to the further info links

Inside the `<div>` with the class of `further-info` you will find four `<a>` elements — each one linking to an interesting Mozilla-related page. To complete this section you'll need to insert an `<img>` element inside each one containing appropriate `src`, `alt`, `srcset` and `sizes` attributes.

In each case (except one — which one is inherently responsive?) we want the browser to serve the 120px wide version when the viewport width is 500px wide or less, or the 400px wide version otherwise.

Make sure you match the correct images with the correct links!

### An art directed red panda

Inside the `<div>` with the class of `red-panda`, we want to insert a `<picture>` element that serves the small portrait panda image if the viewport is 600px wide or less, and the large landscape image otherwise.

[More about the assessment](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Structuring_a_page_of_content).
