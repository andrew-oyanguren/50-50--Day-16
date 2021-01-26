# 50-50--Day-16
Button Ripple Effect

## Table Of Contents
* General Info
* Technologies Used

### General Info
This project was short and sweet, but a great way to help me further my understanding of mouse positions. 
I created a span element that I had styled in my css to give a ripple effect essentially just scaling from 1 to 3.
I use the clientX and clientY mouse properties to store the mouse x and y axis in variables an subtracted that by the cordinate of my button,
which I found using the offsetTop and offSetLeft properties. After creating the span ripple, I then removed it in a timeout function after 500 ms.

### Technologies Used
* HTML
* CSS
* JavaScript