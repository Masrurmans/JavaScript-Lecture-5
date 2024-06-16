# Methods in JavaScript
### String 
### Numbers 

# Today we are gonna learn String methods

# What is a method in JavaScript
 In JavaScript, methods are used to manipulate objects. They are written in the same way as functions, but they are defined within the object. Methods are usually used to access and manipulate the data stored in an object. For example, you can use the length method to find out the length of a string.

### JavaScript string methods
- charAt     
- at()
- concat()
- trim()
- includes()
- indexOf()
- replace(), 
- replaceAll()
- repeat()
- slice()
- substring()
- split()
- toString()
- toLowerCase()
- toUpperCase()

### Method ```charAt()```
The charAt in JavaScript is used to find the character at the specified index value of the String. 
``````js
let str = "Hello, World!";
let char = str.charAt(1); // Retrieves the character at index 1
console.log(char); // Output: "e"
```````
----
### Method ```at()```
The at() method of String values takes an integer value and returns a new String consisting of the single UTF-16 code unit located at the specified offset.
`````js
let str = "Hello";
console.log(str.at(1)); // Output: "e"
``````
----
### Method ```concat()```
The concat() method concatenates (joins) two or more arrays. The concat() method returns a new array, containing the joined arrays.
`````js
let str1 = "Hello, ";
let str2 = "World!";
let newStr = str1.concat(str2);

console.log(newStr); // Output: "Hello, World!"
console.log(str1);   // Output: "Hello, " (original str1 unchanged)
console.log(str2);   // Output: "World!" (original str2 unchanged)
``````
----
### Method ```replace()```
The replace() method searches a string for a value or a regular expression. The replace() method returns a new string with the value(s) replaced. The replace() method does not change the original string.
`````js
let originalString = "Hello, World!";
let newString = originalString.replace("World", "Universe");

console.log(newString); // Output: "Hello, Universe!"
console.log(originalString); // Output: "Hello, World!" (original string unchanged)
`````
----
### Method ```replaceAll()```
The replaceAll() method of String values returns a new string with all matches of a pattern replaced by a replacement . The pattern can be a string or a RegExp , and the replacement can be a string or a function to be called for each match. The original string is left unchanged.
`````js
let originalString = "Apples are round, and apples are juicy.";
let newString = originalString.replaceAll(/apples/gi, "oranges");

console.log(newString); // Output: "Oranges are round, and oranges are juicy."
`````
----
### Method ```split()```
In JavaScript, the split method allows you to split the string into an array of substrings based on a given pattern. The split() function takes one or two optional parameters, the first one being the separator, and the second the maximum number of elements to be included in the resulting array.
`````js
let str = "apple,orange,banana";
let arr = str.split(",");

console.log(arr); // Output: ["apple", "orange", "banana"]
`````
### Method ```substring()```
The substring() method extracts characters, between two indices (positions), from a string, and returns the substring. The substring() method extracts characters from start to end (exclusive).
`````js
let str = "Hello, World!";
let sub = str.substring(7, 12);

console.log(sub); // Output: "World"
`````
----
### Method ```slice()```
Description. The slice() method extracts a part of a string. The slice() method returns the extracted part in a new string. The slice() method does not change the original string. The start and end parameters specifies the part of the string to extract.
`````js
let str = "Hello, World!";
let newStr = str.slice(7, 12);

console.log(newStr); // Output: "World"
`````
----
### Method ```toLowerCase()```
The toLowerCase() method returns the value of the string converted to lower case. toLowerCase() does not affect the value of the string str itself.
`````js
let str = "Hello, World!";
let lowerStr = str.toLowerCase();

console.log(lowerStr); // Output: "hello, world!"
`````
----
### Method ```toUpperCase()```
The toUpperCase() method returns the value of the string converted to uppercase. This method does not affect the value of the string itself since JavaScript strings are immutable.
`````js
let str = "Hello, World!";
let upperStr = str.toUpperCase();

console.log(upperStr); // Output: "HELLO, WORLD!"
`````
----
### Method ```trim()```
The trim() method removes whitespace from both ends of a string. Note: This method does not change the original string.
`````js
let str = "   Hello, World!   ";
let trimmedStr = str.trim();

console.log(trimmedStr); // Output: "Hello, World!"
`````
----
### Method ```includes()```
includes() method is a JavaScript method that is used to check if a specific string or element is present in another string or array. In this example, the . includes() method is used to check if the myString variable includes the word "world". If it does, it will print "The string includes the word 'world'".
`````js
let str = "Hello, World!";
let isIncluded = str.includes("World");

console.log(isIncluded); // Output: true
`````
----
### Method ```toString()```
This method is used to transform an object into a String. Typically, it is used to construct a string containing the information on an object that can be printed, and we can redefine it for a certain class.
`````js
let num = 123;
let str = num.toString();

console.log(str); // Output: "123"
`````
----
### Method ```indexOf()```
The indexOf() method of String values searches this string and returns the index of the first occurrence of the specified substring. It takes an optional starting position and returns the first occurrence of the specified substring at an index greater than or equal to the specified number.
`````js
let str = "Hello, World!";
let index = str.indexOf("World");

console.log(index); // Output: 7
`````
----
### Method ```repeat()```
repeat() method is used to return String whose value is the concatenation of given String repeated count times. If the string is empty or the count is zero then the empty string is returned.
`````js
let str = "Hello";
let repeatedStr = str.repeat(3);

console.log(repeatedStr); // Output: "HelloHelloHello"
`````

