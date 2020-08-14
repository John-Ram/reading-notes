## Responsive Web Design and Regular Expressions

*Code 301: Class 4*

>"Ahhhhh! You sunk my battleship!"
> The Riddler (Batman Forever)

if you want to play battleship and you're a coder, then **CSS Grid** is probably how you're gonna do it. A more recent development, CSS grid allows you to control the boxes of your html structure more accurately. However at the moment you have use hard written HTML to create your grids, but local sources say that'll change in the upcoming months.

So why **CSS Grid**? Well a good coder knows that you need to create the least amount of work for the maximum amount of results. Say you have 5 divs containing various images and text. 1 needs to be at the top with a hero image, 2 inline with a gap in the middle for space and 3 at the bottom for your footer. you could Manually set the hero to 100% width of the page with say 350px of height to format it. Then position relative you other two images to their respective ends and so on. Grid, takes the complexity and extra lines of code you'd have to write and puts it on a diet. With *grid-template-column* & *grid-template-rows* not only can you set the the dimensions of the boxes but you can also organize them, only adding in padding and margins for the finer details instead of making it the backbone of your astetics and trying to make it work. a word of caution though, if you have two **CSS** files in a group, make sure to agree to use the same **CSS** type otherwise it will confuse the page. Grid will ignore some of the CSS rules you play like float and positioning, so make sure you keep your files compatible.

if you wanna see Grid in action and you like Carrots, then visit [CSS Grid Garden](https://cssgridgarden.com/) and give it a shot. 

Now say you wonder what your favorite word is, or maybe your teacher wants you to reduce the number of 'and's  in your paragraphs. Well docs have that feature, but what about code? that's *Regular Expressions* or Regex for short (they do know it sounds like rejects out of context right?). It allows you to imput parameter's for the exact type of words you're looking for and highlights them. I personally have seen the need for this yet but time will change that. Maybe you can see a use for it though at [Regexr.com](https://regexr.com/).

If you liked this then follow [My GitHub](https://github.com/John-Ram) where more of these posts will uploaded throughout my time at Codefellows.

[Back to Main Page](https://john-ram.github.io/reading-notes.md/)