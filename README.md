Steps of Optimization on pizza.html

Modified views/js/main.js file

(1) modified on function updatePositions by moving the variables defined in for loop out of the loop to reduce the times of selecting all the elements with class 'mover'.

(2) use document.getElementsByClassName('mover') instead of document.querySelectorAll('.mover').

(3) reduce the number of animating pizzas on line 535

(4) image compression on  pizza.png and pizzeria.jpg by using http://compresspng.com/

(5) minify/compress bootstrap-grid.css and style.css files by using http://jscompress.com/ and http://cssminifier.com/


Instructions for viewing the optimized files:

(1) To get started, download the entire directory, `udcity_courses_project4`, and open it in a browser locally.

(2) PageSpeed score of 90 is for index.html , click on index.html and view it by PageSpeed Insights

(3) The frame rate of 60fps for the pizza.html page, click on views/pizza.htm and view it by Chrome Developer Tools - TimeLine


