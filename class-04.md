
# HTML Links, CSS Layout, JS Functions:

Links are created using the <a> element. Users can click on anything
between the opening <a> tag and the closing </a> tag. You specify
which page you want to link to using the href attribute.
 - The <a> element uses the href attribute to indicate the page you are linking to.
 - If you are linking to a page within your own site, it is best to use relative links rather than qualified URLs.
  -  You can create links to open email programs with an email address in the "to" field.
  -  You can use the id attribute to target elements within a page that can be linked to.
  
  - Block-level elements start on a new line
  Examples include: heading , paragraoh , un-ordered list , lists 
  
  - Inline elements flow in between surrounding text :
  examples include :images 
  
  ## Containing Elements:
  
If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.
It is common to group a number of elements together inside a <div> (or other block-level) element. For example, you might group together all of the elements that form the header of a site (such as the logo and the main navigation). The <div> element that contains this group of elements is then referred to as the containing element.
### Controlling the Position of Elements:
  CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative   positioning, and absolutepositioning. You specify the positioning scheme using the position property in CSS. You can also float elements using the float property.
  1. `Normal flow` : Every block-level element appears on a new line, causing each item to appear lower down
the page than the previous one. Even if you specify the width of the boxes and there is space for two elements to sit side-by-side, they will not appear next to each other. This is the default behavior (unless you tell the browser to do something else).
  2. `Relative Positioning` : This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed. This does not affect the position of surrounding elements; they stay in the position they would be in
in normal flow.
  3. `Absolute positioning` :This positions the element in relation to its containing element
  #### The display property :
  The display property is the most important CSS property for controlling layout.
  `Display: none` : is commonly used with JavaScript to hide and show elements without deleting and recreating them.
  
  Override The Default Display Value
   every element has a default display value. However, you can override this.
   **display:none or visibility:hidden** 
   - `display :none` : hiding the elements , The element will be hidden, and the page will be displayed as if the element is        not there
` - `visability:hidden;` : hides an element. the element will still take up the same space as before. The element will be          hidden, but still affect the layout

    ####The position Property:
    The position property specifies the type of positioning method used for an element (static, relative, fixed, absolute or sticky).
   
- position: static;
HTML elements are positioned static by default. 
Static positioned elements are not affected by the top, bottom, left, and right properties.
An element with position: static; is not positioned in any special way; it is always positioned according to the normal flow of the page

- position: relative;
An element with position: relative; is positioned relative to its normal position.

- position: fixed;
An element with position: fixed; is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled. The top, right, bottom, and left properties are used to position the element.

A fixed element does not leave a gap in the page where it would normally have been located.

- position: absolute;
An element with position: absolute; is positioned relative to the nearest positioned ancestor (instead of positioned relative to the viewport, like fixed).

- position: sticky;
An element with position: sticky; is positioned based on the user's scroll position.

A sticky element toggles between relative and fixed, depending on the scroll position. It is positioned relative until a given offset position is met in the viewport - then it "sticks" in place (like position:fixed)

**Overlapping Elements** :
When elements are positioned, they can overlap other elements.

The z-index property specifies the stack order of an element (which element should be placed in front of, or behind, the others).

**Screen Sizes**:
Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.
- Grids help create professional and flexible designs.
**FUNCTI ON** :
Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than rep eating the same set of st atements).
A function created with a function declaration is a Function object and has all the properties, methods and behavior of Function objects. See Function for detailed information on functions.
