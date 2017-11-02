## One to Multi

Build a function that sorts an array into a multidimensional array grouped by data type

- Write a function that takes one parameter 
	- Parameter 1 - An array of anything
- The function should output a multidimensional array grouped by data type
- Example: 
	- `var myArray = ['hello', 34, true, false, 'goodbye', 56, 12, '25', true];`
	- `groupArray(myArray);`
	- Output - `[['hello, 'goodbye', '25'], [34, 56, 12], [true, false, true]]`

    var myArray = ['hello', 34, true, false, 'goodbye', 56, 12, '25', true];
    var obj = {
        'row1' : {
            'key1' : 'input1',
            'key2' : 'inpu2'
        },
        'row2' : {
            'key3' : 'input3',
            'key4' : 'input4'
        }
    };
    var mixed = {
        'row1' : ['input1', 'inpu2'],
        'row2' : ['input3', 'input4']
    };

console.log(numeric);
console.log(obj);
console.log(mixed);


var iMax = 20;
var jMax = 10;
var f = new Array();

for (i=0;i<iMax;i++) {
 f[i]=new Array();
 for (j=0;j<jMax;j++) {
  f[i][j]=0;
 }
}
