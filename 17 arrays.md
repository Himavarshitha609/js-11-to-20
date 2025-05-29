let fruits = ["Apple", "Orange", "Banana"];
console.log(fruits.toString()); // Apple,Orange,Banana
console.log(typeof fruits.toString()); // string
let fruits = ["Apple", "Orange", "Banana"];
console.log(fruits.join("-")); // Apple-Orange-Banana
console.log(typeof fruits.join("-")); // string
let fruits = ["Apple", "Orange", "Banana"];
console.log(fruits.join(" and ")); // Apple and Orange and Banana
let fruits = ["Apple", "Orange", "Banana"];
console.log(fruits.pop()); // Banana
console.log(fruits); // ["Apple", "Orange"]
let fruits = ["Apple", "Orange", "Banana"];
console.log(fruits.push("Pineapple")); // 4
console.log(fruits); // ["Apple", "Orange", "Banana", "Pineapple"]
let fruits = ["Apple", "Orange", "Banana"];
console.log(fruits.shift()); // Apple
console.log(fruits); // ["Orange", "Banana"]
let fruits = ["Apple", "Orange", "Banana"];
console.log(fruits.unshift("Pineapple")); // 4
console.log(fruits); // ["Pineapple", "Apple", "Orange", "Banana"]
