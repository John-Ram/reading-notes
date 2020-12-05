## SMACSS and Responsive Web Design

*Code 301: Class 1*

>
>

Remember back in the old days (10ish years ago) when your brand new Motorola Droid and Thick Iphone one had to view websites on the same window style as your PC? It was like trying to fly a plane with a submerisble viewport, can be done but not a fun experience. That is the point of *Responsive Web Design* and *SMACSS*, According to the Article by [Shay Howe](https://learn.shayhowe.com/advanced-html-css/responsive-web-design/), Ethan Marcotte played a large part in the development of responsive websites including giving the practice it's title. For a while websites were ordered to have a mobile version and a computer version which the user could pick. This ment that for a while there were 2 versions of every site as there wasn't yet way to make the site dynamic to the user's viewport.

*Responsive Web Design* is the front-end practice of making the same site usable across different device types and sizes, integrating the mobile and desktop versions of the previous generation. Rather than set the site up for a desktop first approach and *then* a mobile. They recommend doing the opposite, work on the smaller, easier mobile front-end set up the breakpoints for the larger viewports. One of the ways this is done is by setting minimum and maximum widths and heights to your media query (**@media**) which will check the screen size and adjust to the parameters that you set like an **if** or **else** statement on Javascript. One if the issues you can face with this however is if you have any floats in your code they will stay static in their size instead in going with the follow as it were. So make sure to have those adjusted within your media theme.  The major benefit is that this technically means less work for you to do vs making whole other website for your other users. 

As mentioned before, Floating can be a problem without media queries as the site will adjust the text and other non-floated bits but you have to do so manually for your floaters. Floating still helps in your web design but make sure you give it the proper settings to reduce bugs. At this point Responsive Web is still new but growing pretty fast due to mobile devices, so while a lot of pre-IE 8 systems might not support this, that is quickly being changed.

If you liked this then follow [My GitHub](https://github.com/John-Ram) where more of these posts will uploaded throughout my time at Codefellows.

[Back to Main Page](https://john-ram.github.io/reading-notes.md/)