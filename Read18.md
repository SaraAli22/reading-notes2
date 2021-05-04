# Layout 
## Building Blocks
CSS treats each HTML element as if it is in its
own box. This box will either be a block-level
box or an inline box.
Block-level boxes start on a new line and act as the main building blocks
of any layout, while inline boxes flow between surrounding text. You can
control how much space each box takes up by setting the width of the
boxes (and sometimes the height, too). To separate boxes, you can use
borders, margins, padding, and background colors.

**Block-level elements**
start on a new line
Examples include:
h1> p> ul> li>

**Inline elements**
flow in between
surrounding text
Examples include:
img> b> i>

# Containing Elements
If one block-level element sits inside another
block-level element then the outer box is
known as the containing or parent element.

It is common to group a number of elements together inside a div>
(or other block-level) element.

For example, you might group together
all of the elements that form the header of a site (such as the logo and
the main navigation). 
The div> element that contains this group of
elements is then referred to as the containing element.

# Controlling the Position of Elements
CSS has the following positioning schemes that allow you to control
the layout of a page: normal flow, relative positioning, and absolute
positioning. You specify the positioning scheme using the position
property in CSS. You can also float elements using the float property.

* Normal flow
Every block-level element
appears on a new line, causing
each item to appear lower down
the page than the previous one.
Even if you specify the width
of the boxes and there is space
for two elements to sit side-byside,
they will not appear next
to each other. This is the default
behavior (unless you tell the
browser to do something else).

* Relative Positioning
This moves an element from the
position it would be in normal
flow, shifting it to the top, right,
bottom, or left of where it
would have been placed. This
does not affect the position of
surrounding elements; they stay
in the position they would be in
in normal flow.

* Absolute positioning
This positions the element
in relation to its containing
element. It is taken out of
normal flow, meaning that it
does not affect the position
of any surrounding elements
(as they simply ignore the
space it would have taken up).
Absolutely positioned elements
move as users scroll up and
down the page.

 ## To indicate where a box should be positioned,
  you may also need to use
box offset properties to tell the browser how far from the top or bottom
and left or right it should be placed. 
* Fixed Positioning
This is a form of absolute
positioning that positions
the element in relation to the
browser window, as opposed
to the containing element.
Elements with fixed positioning
do not affect the position of
surrounding elements and they
do not move when the user
scrolls up or down the page.

* Floating Elements
Floating an element allows
you to take that element out
of normal flow and position
it to the far left or right of a
containing box. The floated
element becomes a block-level
element around which other
content can flow.

# Screen Sizes
Different visitors to your site will have different sized screens that show
different amounts of information, so your design needs to be able to
work on a range of different sized screens.
# Screen Resolution
Resolution refers to the number of dots a screen shows per inch. Some
devices have a higher resolution than desktop computers and most
operating systems allow users to adjust the resolution of their screens.
# Page Sizes
Because screen sizes and display resolutions vary so much, web
designers often try to create pages of around 960-1000 pixels wide
(since most users will be able to see designs this wide on their screens).
# Fixed Width Layouts
Fixed width layout
designs do not
change size as the
user increases
or decreases
the size of their
browser window.
Measurements tend
to be given in pixels.
# Liquid Layouts
Liquid layout designs
stretch and contract
as the user increases
or decreases the
size of their browser
window. They tend to
use percentages.

 * div> elements are often used as containing elements
to group together sections of a page.

* Browsers display pages in normal flow unless you
specify relative, absolute, or fixed positioning.

* The float property moves content to the left or right
of the page and can be used to create multi-column
layouts. (Floated items require a defined width.)

* Pages can be fixed width or liquid (stretchy) layouts.

* Designers keep pages within 960-1000 pixels wide,
and indicate what the site is about within the top 600
pixels (to demonstrate its relevance without scrolling).

* Grids help create professional and flexible designs.

* CSS Frameworks provide rules for common tasks.

* You can include multiple CSS files in one page.
![image](data:image/png;base64,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)
![image](https://i1.wp.com/css-tricks.com/wp-content/uploads/2019/06/sections-diagram.png?resize=1024%2C656&ssl=1)



