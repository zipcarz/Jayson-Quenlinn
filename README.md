Jayson-Quenlinn
===============

var a = { what: "A regular JS object" },  
  b = $( "body" );  
   
if ( a.jquery ) { // Falsy, since it's undefined  
  alert( "a is a jQuery object!" );  
}  
   
if ( b.jquery ) { // Truthy, since it's a string  
    alert( "b is a jQuery object!" );  
}  
alert( "You are running jQuery version: " + $.fn.jquery );  
