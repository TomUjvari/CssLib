# CssLib
My personal library of reusable CSS classes, inspired by [Bootstrap](https://getbootstrap.com) with more modern designs and a far more explicit syntax.  
This projet is still in early development and lacks many feature compared to competitors.  
Check the **examples** folder to see examples on how to use it.


## How to use
It is highly recommended you put the entire page content into a div with the `wrapper` class.  
Here's a rundown of how to use the included classes. unless specified otherwise, all classes are meant to be applied to `<div>` elements.

### Positioning
You can position a div's children by adding the following classes to the container:
-  **col / row** - Set the container to column or row layout
-  **left / right / center** - Horizontal alignment
-  **top / bottom / middle** - Vertical alignment
-  **centered** - Center everything at once
-  **fill-w** - Sets width to 100%
-  **fill-h** - Sets height to 100%
-  **space-fill** - Children fill the container, roughly taking equal space (`flex: 1`)
-  **space-equally** - All children take equal space (`grid`), set the amount of rows or columns with `--rows: x` and `--cols: x` in the style.
-  **auto-grid** - Reponsive grid via auto-fill
-  **auto-grid-fill** - Reponsive grid via auto-fit (the naming is confusing but 'fill' is more accurate to its behavior)

### Rounding
-  **rounded-light/medium/heavy** - Applies rounding with specified intensity
-  **rounded-max** - Rounds to the maximum without turning the div into an ellipsis
-  **rounded-ellipsis** - Rounds the div into an ellipsis

### Div Styles
-  **glass** - Gives a glassmorphic design to the div
-  **clickable** - Makes a glass div react on hover and click

### Image Cropping
-  **crop-square** `<img>` - Crops the image into a square
-  **crop-circle** `<img>` - Crops the image into a circle

### Buttons
-  **button-neutral**
-  **button-green**
-  **button-blue**
-  **button-red**

### Forms
-  **form-input-container** - `label` and `input`/`select`/`textbox` children are aligned one above the other, aligned to the left.
-  **form-checkbox-container** - `label` and `input` children are next to eachother

## What each file does
-  **main.css** - Contains positioning and basic styling classes
-  **navbar-horizontal.css** - Horizontal navbar at the top center of the screen
-  **navbar-vertical.css** - Vertical navbar at the middle left of the screen