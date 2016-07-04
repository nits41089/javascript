# javascript
Important files to remember for javascript

If you have a number but need to print it on the screen, you need to convert the value to a string, and in JavaScript this conversion is called "coercion."

Static typing
Dynamic typing

The proper way to characterize them is that == checks for value equality with coercion allowed, and === checks for value equality without allowing coercion;

Anonymous function
var foo = function() {
    // ..
};

function named bar though reference to it is also assigned to x.
var x = function bar(){
    // ..
};

immediately invoked function expression (IIFE)
(function IIFE(){
    console.log( "Hello!" );
})();
// "Hello!"
