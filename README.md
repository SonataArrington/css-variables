Javascript Day/Project 3 of 31


The css variables created allows yoou to use javascript to change the css after it is loaded into the browser.

You declare them on an element or root(which is the highest element similair to html element in an html file) 
and set variable to it the same way you would  any other css ACCEPT these variables have a two dash prefix.

    :root {
        --base: #b9b8f1;
    }


Then you create a constant variable -     const inputs = document.querySelectorAll('.controls input');
to call the .controls  class and the input tags in the document.

The handleUpdate function:

Inside the input fields we set data-sizing to px. Inside the function we call it under the const suffix.

In this project:

* reinforcing data-*
* array vs. node list
* .each is used for an array and forEach is used with a node list 
* .setProperty to set or modify existing css