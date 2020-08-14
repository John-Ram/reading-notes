## CSS Transforms, Transitions, and Animations

*Code 201 Class: 14A*

>“Change starts in your thoughts.”
>Anonymous

Remember when you you were playing those old but awesome Playstation 2 games and some of their loading screens involved the logo spinning? Well guess what this topic is about. Well thanks to the wonderful powers of CSS, Shay Howe shows you how you can animate your logo to do the same! Her [Article](https://learn.shayhowe.com/advanced-html-css/css-transforms/) goes into the details and honestly provides a good read. A brief overview on it shows you step by step the ability to make the box and it's dimensions alter in either a 3d or 2d format, however since CSS3 is still pretty new some it of might not work as intended so as the instructions say, you should apply the proper vendor tags for easier operation. 

Example:

HTML: <figure class="box-1">Box 1</figure>

CSS: .box-1 {
  transform: rotate(20deg);
  transform: scale(.75);
  transform: skewX(5deg);
} 

The following code above translates to the following (roughly): "Box One please scale down to 3 quarters of your size, slanted at an angle of 5 degrees, and rotate clockwise at 20 degrees. So you can relive the days of making your loading screen being animated through a spinning logo. a cool trick if you're an Inception fan is to create a box with a picture of a top and format it to spin either when hovered over or constantly. 

If you liked this then follow [My GitHub](https://github.com/John-Ram) where more of these posts will uploaded throughout my time at Codefellows.

[Back to Main Page](https://john-ram.github.io/reading-notes.md/)