# grid-template
Grid template for Landing Page assignment

## How to download files
1. Click the green "Clone or Download" button.
2. Choose "Download Zip"
3. Unzip the file on your computer by double-clicking (OSX), or right-clicking and selecting "Extract all" (Windows).
4. Move the "landing-page" folder out of your Downloads folder to your local-directory folder for class.

## File Structure
The folder includes one HTML file called "index.html" and a folder called "css" that contains "styles.css" 

Remember:
* Content goes into HTML files.
* Visual styles and layout are managed in CSS.

Open the HTML file in a web browser and in Brackets, to examine the structure of the website and how it is defined in the code. There are extensive comments to help you find your way around (comments will appear grey)


## 12 Column Grid

The layout uses [CSS Grid](https://www.w3schools.com/css/css_grid.asp) to create a 12 column grid for the various sections of content.

Any content within the `container` div can be placed onto the 12 column grid by specifying the CSS property [grid-column](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-column):

`grid-column: span 12` Full width of container

`grid-column: span 6` Half width of container

`grid-column: span 3` One quarter width of container, or 3 columns of 12.

`grid-column: 2 / 4` Section begins at grid track 2 and ends and grid track 4. Tracks are the vertical lines that define columns. 

When the browser is resized to below 600px wide, all the columns will occupy the full width of the screen. This is a common technique for displaying content on mobile devices. 


