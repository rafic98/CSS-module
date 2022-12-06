# In this folder Advanced css properties will be explained

## position CSS property:

    position: ;
    the position CSS property is used to position elements on the page
    takes 5 values:
        1) Static
        2) Relative
        3) Absolute
        4) Fixed
        5) Sticky

### Static positioning

    Static is the default value of position

    The browser will automatically add this property

    It means that the CSS elements will follow the normal flow of the html elments

### Relative positioning

    Similar to static, yet it lets you change the position of your element reletie to its origonal value

    it allows you to specify (top, bottom, left, and right) Css properties to the position of the element.

    Note: even if the element is moved, its origonal place will remain reserved. that means elements around it will act as if it is in its origonal place and it did not move.

### Absolute positioning

    Removes the element from the normal document flow
    Allows you to position it using the top, bottom, left and right css properties

    the element in this case is positioned acording to the html document, or any parent that has relative positioning applied to it

    Note:when you apply Absolute positioning to an element, other elements will ignore it, as if it was never there.

### Fixed

    Means that the element doesnot scroll with the page
    top bottom right and left properties apply
    it is out of the flow of the document

### sticky

    Sticky position is a combo of relative and fixed
    It changes to relative positioning or fixed positioning based on the user's scrolling
