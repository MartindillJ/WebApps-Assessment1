# WebApps-Assessment1

A website is a collection of organised webpages, made up of pictures, video and text. The author has designed this website for fans of his favourite movie, Star Wars (1977).

The website is made up of four pages:

• A home page

• Introduction to the film, the franchise and director, etc.

• Plot summary, teaser trailer, trivia, and

• A table containing actor profiles.
     
     
Each page follows the same layout:

• A header

• Navigation

• Main (and/or aside) and, with the exception
of the home page

• A footer

The author believes that simple two-to-three box layouts are especially easy to see and digest, to navigate and find content, all without overloading the user (by having too much on-screen at any one time). Also, this layout is relatively easy to style responsively.

The author decided to base his website on a 12-column CSS grid (1-column for mobiles) because 12 is divisible by 2, 3, 4 and 6. Having written the CSS, the author has a lot more control over how the website responds to the user when resized (or viewed on another device). style.css contains special rules triggered by media queries (four breakpoints in total, fluid design). Put simply, the boxes or columns stack differently depending on the device and column width is relative. Borders and margins (white space in general), as well as pictures and video shrink due to the lack of space and, depending on the content, may disappear altogether.

These style choices were made so that content, no matter what, could be displayed in different ways without losing its meaning or structure. Text, for example, is always easy to read and containers move and act in a predictable way. Also, pictures/video have text alternatives, just encase browsers are unable to locate their respective jpg/mp4 files.


Additionally, the author spent some time picking three Google fonts to replace the browser defaults for body, h1, h2 and h3 elements. Sans-serif typefaces were picked for headings because the author believes they are bold easy to read at larger sizes. Serif typefaces were chosen for the body, in general, to maximise paragraph legibility and base font size was increased to 20px (much larger than originally thought necessary) to ensure readability.


The author decided on a minimal three-colour pallet, based on his favourite piece of Star Wars concept art, to ensure consistent theming:

• A clear white background (off-white header, footer and dropdown menu)

• Not-too-dark text (blue-green hue) and navbar (white text)
(Web Accessibility Contrast Ratio 7.46:1), and

• A bluey accent colour for the .active class and when hovering over links

The RGBA colour model was used when declaring colour in CSS. At the start of the project, the author believed this model was superior to hexadecimal colour because of the added alpha channel. By adjusting this channel the author could change elements opacity and stacking order (or z-index) without writing additional declarations. Sadly, however, this function wasn’t really used, and having done some research the author now sees that hex values are much more popular. Regardless, RGBA values were used consistently throughout the project, as the author believes this makes it easier for other developers to understand and, possibly, work on in future.

Just one set of images (with relatively high resolution) was used when creating this website. Websites are pixel based, and if images aren’t large enough they may appear pixelated when blown up on larger screens. Given the time, the author would have liked to create a set of smaller images for mobile devices, however as the image size in KB is comparable to page size, these considerations were ignored. The same cannot be said about the trailer on storyline.html. Unfortunately, this was the only mp4 file available (Credit: 20th Century Fox/LucasFilm).

On reflection, the author would have liked to spend more time playing with the design on paper and sketching wireframes before creating a grid, and writing the HTML/CSS. While the website is, I hope, clear and the code easy to read, the author spent a lot of time writing and re- writing HTML, attempting to use semantic elements correctly. Starting with a clear layout and design plan would have saved a lot of time later on in the project.

Also, the author would like to have used different CSS files for each device type. Designed for mobiles first (due to popularity), it got confusing in the middle of the project adding a suitable number of breakpoints, and writing CSS rules affecting the content displayed.

In future, the author will probably use just two fonts for headings and body text respectively. Also, in hindsight, maybe this pallet doesn’t really show enough colour variation. Again, in future, the author will probably use a fun four-colour pallet, something professional (crisp and clean), but with warm, high contrast, accent colours. The author believes these colour palettes or schemes are more welcoming, and hexadecimal values will be used.

In conclusion, the author is quite happy with the result. The author’s particularly proud he was able to include a dropdown menu in the nav element (W3Schools, see aNewHope.html [lines 59-65]) and CSS slideshow on the home page (SNOOK, see style.css [lines 166-171]). That said, there’s always room for improvement and the author would have liked to add more content and, perhaps, show off a more complex layout.

The website was tested in Chrome using Developer Tools and on the authors mobile telephone (Sony Xperia Z3 [AndriodTM verision 6.0.1]).
