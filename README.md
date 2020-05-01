# jQuery_color_clicker
Click and change the colors by using jQuery traversing method.

1. Click the middle small box to change the color of the big box.
2. Click the left or right hand box to change the color of the box's siblings.
3. Click the big box to change the color of BOTH boxes.
4. Clicking the reset button will reset to its original background colors.

## Note: 
1. event.stopPropagation() functions prevents the .click() method from propagating from the child element to the parent element because, technically, when you click the smaller boxes, you are also clicking the big box too. This function allows us to make the .click() event exclusively for the small boxes and not the big boxes. 

2. random_color() function that is defined in the template will return a random hexadecimal value that can be used as a background coloring