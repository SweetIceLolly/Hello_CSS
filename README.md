# Hello_CSS
My first CSS practice!

# What does it do
- ABSOLUTELY NOTHING BUT A STUPID UI

# Knowledge involved
- Navigation bar
- Leftbar
- Vertical navigation bar
- Dropdown (button, description, image)
- Tooltip
- Insert background image for textbox
- Pagination
- Button
- Sprites
- Normal table
- Single line table
- transition
- linear-gradient
- box-shadow

# Study notes
1. Sans-serif fonts are considered easier to read than serif fonts. (https://www.w3schools.com/css/css_font.asp)
2. Do NOT use large fixed width elements
3. NEVER make a webpage that requires the user to scroll horizontally (https://www.w3schools.com/css/css_rwd_viewport.asp)
4. Design for mobile first. (https://www.w3schools.com/css/css_rwd_mediaqueries.asp)
5. Grid-View is a good idea to design. Use percentages. (https://www.w3schools.com/css/css_rwd_grid.asp)
6. Five groups of device:
Copied from https://www.w3schools.com/css/css_rwd_mediaqueries.asp
```css
/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {}

/* Small devices (portrait tablets and large phones, 600px and up) */
@media only screen and (min-width: 600px) {}

/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {}

/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {}

/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {}
```
7. Use `input[type="xxx"]` to select elements in forms. e.g.: `input[type="text"]`
8. To calculate style priority (Larger = Used):
```txt
Reference: https://www.w3schools.com/css/css_specificity.asp
1000: style attribute (i.e. <elem style="xxx"></elem>)
100:  id (i.e. #xxx {*})
10:   attribute, class or pseudo-class (e.g. .popup {*})
1:    element name or pseudo-element (e.g. h1 {*})
```
