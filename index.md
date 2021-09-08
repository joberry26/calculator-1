https://www.w3schools.com/js/js_best_practices.asp

https://code.tutsplus.com/tutorials/24-javascript-best-practices-for-beginners--net-5399 

https://www.thinkful.com/learn/javascript-best-practices-1/

1. Always declare local variables and place declarations at the top.
2. Do not use new obj()
3. Beware of automatic type conversions: A variable can contain all data types as well as change its data type.
4. Use parameter defaults: if a function is called with a missing argument it is then set to undefined which can break your code.
5. Use a debugger: JSLint is a debugger written by Douglas Crockford. Simply paste in your script, and it'll quickly scan for any noticeable issues and errors in your code.
6. Place script at the bottom of your page.
7. Reduce global footprint, by doing such you significantly reduce the chance of bad interactions with your code.
	This:
	var DudeNameSpace = {
   name : 'Jeffrey',
   lastName : 'Way',
   doSomething : function() {...}
}
console.log(DudeNameSpace.name); // Jeffrey

	vs:
Example: var name = 'Jeffrey';
var lastName = 'Way';
 
function doSomething() {...}
 
console.log(name); // Jeffrey -- or window.name
8. Comment as much as needed, but not more.
9. Remember the semicolons.

10.  Build Modular, specialized functions. Don’t have one function that runs everything
