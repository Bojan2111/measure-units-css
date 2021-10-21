# Sample presentation of CSS measurement units

This quite simple HTML page was designed to show the difference between different measurement units in CSS. Absolute units are fixed units and don't change with changing the screen size, but relative are quite different.

## Absolute Units
- cm centimeters
- mm millimeters
- in inches (1in = 96px = 2.54cm)
- px * pixels (1px = 1/96th of 1in)
- pt points (1pt = 1/72 of 1in)
- pc picas (1pc = 12 pt)
## Relative units
- em Relative to the font-size of the element (2em means 2 times the size of the current font)
- ex Relative to the x-height of the current font (rarely used)
- ch Relative to the width of the "0" (zero)
- rem Relative to font-size of the root element
- vw Relative to 1% of the width of the viewport*
- vh Relative to 1% of the height of the viewport*
- vmin Relative to 1% of viewport's* smaller dimension
- vmax Relative to 1% of viewport's* larger dimension
- % Relative to the parent element
## About the display
When looking at the graphical presentation, keep in mind the following:
- For all units, divs are of width and height of 10 units,
- The font size is 3 units,
- For relative units, their parent div has a font size of 10px,
- Body element has a font size of 16px.
### Sorry for not so trendy CSS design
I wanted to keep this page as simple as possible, just to show the difference and existance of different CSS units. All suggestions welcome. Thanks!
* part of the text is copied from [W3 Schools](https://www.w3schools.com/cssref/css_units.asp)
