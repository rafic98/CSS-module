# Notes on commonly used Css propertirs

# Fonts

## Color

    color: ; property that changes the text color

## font-size

    font-size: ; changes the size of the font, in px, rem,em, and %

## font-style

    font-style: takes to values, oblique,and italic
        not all fonts support oblique, if the style is not supoorted, the style will switch to italic

## font weight

    font-weight: ;
        the default = 400,
        the higher the number the thicker it the font its
        you can set the value to bold which sets the font weight to maxinmum

## font align:

    text-align: ;
        changes the alignment of the text
        options: right, center (left which is default)

## text-decoration:

    text-decoration: ;
        can underline, overline or line through your text
        options: overline
                 underline
                 line-through

## line height:

    line-height: ;
        changes the vertial spacing between the lines

# Size of html elements

## width

    width: ;
        changes the width of the element

## height

    height: ;
        sets the height of the element
        - Note that if the amount of content inside the element is going to be more than its height, the data(text) will overflow
        can be specified in %

## background-color

    background-color: ;
    changes the background color of the element

## background image

    backgorund-image: url();
    sets an image to the background of the element
    in the url specify the url of the img u want to use

### properties that allow you to change properties of the background image:

#### background-size: ;

        allows you to change the size of your background image
        you can set it to (contain)
            in this case it will be contained inside the element, note itcan be repeated
        you can set it to (cover):
            but it can also not use the whole image
        you can set in values:
         which will change the size of the background image
         best choice will be background-size:100%;

#### background-repeat: ;

        you can specify how you want the image to repeat, and if not you can set the value to no.
        repeat-x will only repeat in horizontal direction
        repeat-y will repeat in vertical direction

#### backgourn-position: ;

        this allows you to move your backgrounds initial postion it can take more than one option:
        first option is virtacly
        second option is horizontaly
        -options:
            bottom, center, top
