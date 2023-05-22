### Q.1 Whats Box Model in CSS & Which CSS Properties are part of it ? (2 Marks)
- box Model is the concept which describes how the HTML elements are modeled and defined in browsers, such as padding, border, margin etc..
- Content - everything behaves like a box
- Padding - The space we add on top of the main content
- border - the border is the space added on top of our main content + padding
- Margin - to put some whitespace b/w the content and the main screen.
### Q.2 What are the Different Types of Selectors in CSS & what are the advantages of them? (2 Marks)
- CSS selectors define the pattern to select elements we sets a set of CSS rules to be applied.
- universal selector : selects all elements. denoted by *
- Type selector : selects all elements which have the given node name, <elementname>
- class selector : selects all the elements which have same class attribute, .className
- id selector : selects element based on the value of its id attribute, #idname

### Q.3 What is VW/VH & How its different from PX? (2 Marks)
- Vw & Vh are the relative units which scales better on different devices.
- viewWidth : 1vw is 1% of the width of the viewport.
- viewHeight : 1vh is 1% of the height of the viewport.
- px : which specifies the fixed size and does not change based on other element.

### Q.4 Whats difference between Inline, Inline Block and block ? (3 Marks)
- Block : always start on new line and takes up the full width available.
- Inline : elements do not start on new line and takes the width as necessary.
- Inline-Block : combines the behaviour of both, by being placed as inline elements but behaves as block elements.
### Q.5 How is Border-box different from Content Box? (2 Marks)
- Border-Box : padding and border are included inside the box.
- Content-box : wadding and wborder takes the space outside the element.

### Q.6 What’s z-index and How does it Function ? (2 Marks)
- z-index is used to specify the stack order of an element and determines which element to be placed in front or behind other elements when they overlap.

### Q.6 What’s Grid & Flex and difference between them? (5 Marks)
- Grid
  - 2-dimensional layout with rows and column, which makes easier to design the web pages without using float & positioning.
  - works with both row and column.
- Flex
  - 1-dimensional layout, helps in allocating & alligning the items in the container.
  - This works with either row or column

### Q.7 Difference between absolute and relative and sticky and fixed position explain with example. (5 Marks)
- Absolute
  - will adjust its position wrt its parent.
  - this takes the elements out of the regular document flow while also affects the layout of other elements on the page.
- Relative
  - will adjust from its normal position,
  - elements move around while still remaining in the regular document flow.
- Sticky
  - elements are positioned based on user's scroll position.
  - effects the flow of other elements in the page,
  - it is defined inside some other container, If container has overflow, depending on the scroll offset it turns to position fixed.
- Fixed
  - element is fixed position is displayed wrt the viewport or the browser window.
  - Stays in same place, even if page is scrolled
  - does not effect the flow of other elements

### Q.8 Build Periodic Table as shown in the below image (10 Marks)


### Q. 9 Build given layout using grid or flex see below image for reference . (5 Marks)


### Q.10 Build Responsive Layout both desktop and mobile and Tablet, see below image for reference ? (10 Marks)


### Q.11 Build Complete Homepage of Ineuron ( Link ) with responsiveness. (10 Marks)


### Q.12 What are Pseudo class in CSS & How its different From Pseudo Elements? (2 Marks)
- PseudoClass are used to target elements thats in specific state.
  - preceded by single colon
  - hover over mouse pointer
- PseudoElements are used to target specific parts of an element.
  - preceded by double colon(::)
  - Ex: firstLetter, firstLine or to insert content before or after the element.
