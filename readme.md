
# HTML-CSS Assignment

## Layout structure 

* In the HTML structure , we have a header tag and below it we have a main tag , inside both these are flexed with justify-content : center , so that the underlying div with width 90% lies in the center of the page exactly and this whole theme is followed throughout the page even for the main div as well.

* In the CSS , for the header part , we have used flex in all the divs , because we want to the inner divs to autometically align themselves veritically and horizontally as we change the width of the screen changes

* In the main body portion , we have used grid layout because we had arrange cards in 2-dimensions , and hence we want that the number of columns are fixed when the user switches from desktop to laptop to phone , in this case , we have choosed to have 4 columns in the desktop, 3 for tablet and 1 for phone view .

* Throughout the assignment, I have used Poppins font-style with font-weight as 800(bold) and 400 (regular) respectively , because it looked the most identical with the target visual that we were given.

* We only have a single page , which the inner centered container is scrollable using property overflow of the y axis as auto .

* Media queries are used to keep the website responsive , in this website , if the width of the viewport is <= 920px , the number of columns in the card grid is 3 . If the width of the viewport is <= 700px the number of columns become 2 . If the width of the viewport is <= 470px , then the number of columns becomes one.This way we display the number columns according to the width of the device keeping our website responsive throughout all the widths.