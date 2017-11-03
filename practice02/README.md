## Total Reverse 

Build a function that takes in an array and reverses it

- Write a function that takes one parameter
	- Parameter 1 - An array of anything
- The function should output an array that is in reverse order from the input array
- Example: 
	- `var myArray = ['hello', 45, 'Bob', 'what', '23'];`
	- `arrayReverse(myArray);`
	- Output - `['23', 'what', 'Bob', 45, 'hello']`
- Avoid using pre-built functions that do something similar

function reverseString (str){
	if (str === "")
	return "";

	else 
	return reverseString (str.substr(1)) + str.charAt(0);
}

reverseString ("Hello");
console.log(reverseString ("Hello"));

document.getElementById('root').innerHTML = reverseString("Hello");



===============================
var myArray = ['hello', '45', 'Bob', 'what', '23'];
console.log( 'Normal Order ' + myArray);
var reversed = myArray.reverse();

document.getElementById("root").innerHTML = myArray;
//myArray.reverse(); equals to var myArray
console.log( 'Reversed ' + reversed);

function reverseString(){
  myArray.reverse();
  document.getElementById("reverse").innerHTML = myArray;
}
console.log(myArray);
reverseString();

