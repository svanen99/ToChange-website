Hi Lisette!

Very well done, I especially liked the role of "Biscuit Director"!

As you can see below you have ticked most of the boxes, and what is left are pretty quick fixes.

So you have a Godkänt grade right now, great work!

If you want the VG grade the most important thing to fix are the <h1>, the responsiveness on mobile of te about page, and the CSS organisation. The first two are really quick fixes, the CSS will take a but longer but it's mainly copy pasting and deleting repeated code. You've already done the work, just need to clean it up.

Please let me know what yiu want to do - there is no time limit on resubmitting, and as said it should be relatively quick to fix up. I should be available most times in the rest of the week, so don't hesitate to get in contact if you have any questions.

*************************************

CRITERIA FOR GRADING

*************************************

GODKÄNT:
-------------------------------------

3 separate pages: ✔

A header with a page title on every page: ✔ ❌
    You have an <h1> on each page, which is great BUT they need to have unique content for SEO reasons. Google doe not like repeated content.

A navigational menu every page with links to the other pages: ✔

Contact form: ✔
    Email: ✔
    Message: ✔ 
    Required: ✔ ❌
       According to the assignment specs the message should also be required
    Mail to: ✔

RWD:
    Desktop: ✔
       .columns have 33% width but they are not inside a flex container so don't appear side by side. It doesn't break anything, but it looks a bit weird.
    Mobile: ✔ ❌
        On the about page, check the generated widths of .column elements.
        Hint: look at the box-model and box-sixing property.
External CSS: ✔

-------------------------------------

VÄLGODKÄNT:
-------------------------------------

Current page indication in the menu: ✔

Responsive Image: ✔
    Purrfect!

RWD:
  Media Query: ✔
  Flex/Grid: ✔ ❌
     Flex is good; 
     grid is declared in index.css but the are values are invalid (you can see the error in the console - if you use commas in the grid-template-area property it breaks) and none of the children are assigned to the areas.

Separate CSS: ✔ ❌
    Lots of repetition in the css files, for example you have the exact same header and nav styles in all 3 files.
    Create a "global" CSS file for all the common elements like the header, nav, footer, media query etc. Then import that file into every page. An html page can import unlimited CSS files.
    The rule of coding is that if you have written the same thing twice you could do it in a better way!
  Semantic: ✔
    Very well done

Semantic Element naming: ✔
  "article first", "article second"  is better then "first-article" because you could have styling on ".article" and give it to all elements without having to repeat code

Code Style:
  Directory names should be in english and in lower case.
  A few missed indentations and in the CSS blocks of code should always have an empty line under them, but generally excellent.
  HTML: ✔
  CSS:✔