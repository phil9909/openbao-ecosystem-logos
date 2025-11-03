# Logo Requirements

## SVG

We currently only accept logos in SVG format

## Light and Dark mode

The OpenBao Website has a light mode and dark mode.
Please ensure that your logo looks good on a light and dark background.

i.e. Make sure the background is transparent and not white or black.

## Padding

Please make sure that your logo fills the whole `viewBox` of the SVG. This means
there should be no blank space left, right, above or below the logo. We require
this, to ensure your logo looks consistent with the other logos on the page and
not much smaller (as we use a fixed height to display the logos). We ensure
proper padding.

You can easily do this with Inkscape (an OpenSource vector graphics editor
available for all major Operating System), be opening the SVG and the selecting
"Edit" > "Resize Page to Selection" and then "File" > "Save as..." and select
"Plain SVG". Or use this script:

```bash
inkscape --actions "select-all;fit-canvas-to-selection" --export-plain-svg --export-overwrite your-logo.svg 
```
