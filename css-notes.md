# CSS Notes


## CSS make-up

*See page 232 in jon duckett book*

Name|Description
---- | ----
Selector| indicate which element the rule effects. ex: p
Declaration| sit inside the braces. ex: {color: green;}
Property| what you want to change in the element. ex: Color
Value| the setting you want to use for the chosen properties. ex: green

> p {
    color: green;
}

## Types of selectors

*See page 238 in jon duckett book*

Name|Description
----- | -----
Type| matched element names
Class| matches the class attribute that is specified after a period. Cover multiple text.

ID| Matches the value of the one that is specified after the hashtag symbol. Used for specific parts of the page.
Child| matched the element that is a direct child of another
Descendant| Matches an element that is a descendant of another element ex: p a {}
Adjacent sibling| Matches the next sibling of another.
General sibling| Matches and element that is a sibling of another although it does not have to be the directly preceding element.

> How rules cascade - **Last rule** can override by **Specifity** and if you put **!** after any property value it is most important. **Specifity** = Type>Class>ID

*you can apply styles internally to the HTML file. \<body style="background-color: color;">

## Color

*See page 250 in jon duckett book*

Type| Description| Values
---- | ---- | ----- |
Foreground Color| Specify the color of text| color: (RGB, HSL, Color name);
Background Color| Sets the color of the background in a box| background-color: (RGB, HSL, Color name);

### Types of color

Type| Description| Example
---- | ---- | ----
RGB Values| Values for red, green, and blue are expressed as number between 0 and 255.| rgb("red","Green","blue")
Hex codes| Represents red, green and blue in hex decimal| #66cdaa
Color Name| Predefine names | Aqua, Green, Blue
HSLA| Hue Saturation Lightness Alpha| hsl(0, 100%, 100%, 0.5)
HUE| the actual color
Saturation| How much gray is in a color
Brightness| How much Black is in a color
Alpha | this is the transparency or **Opacity**
Contrast| **Low contrast** is between background and foreground is hard to read. **High contrast** is easier to read. **Medium contrast** is good for long spans of text.

## Types of text

Type| Description| Example
---- | ---- | ----
Font-size|changes the size of the font| font-size: 100px;
Font-family| Specifies the typeface| font-family: arial, verdana, sans-serif;
font-weight|  Bold or normanl