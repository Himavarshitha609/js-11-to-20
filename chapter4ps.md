let str = "Hello World";
console.log(str.includes("Hello")); // true
console.log(str.startsWith("Hello")); // true
console.log(str.endsWith("World")); // true

console.log(str.includes("harry")); // false
console.log(str.startsWith("new")); // false
console.log(str.endsWith("new")); // false
let str = "Hello World";
console.log(str.toLowerCase());
let str = "Total: Rupees 2907";
console.log(str.slice(13));
let str = "Hello World";
str[3] = "z"; // 3rd index is 4th character 
console.log(str); // Hello World | No change
