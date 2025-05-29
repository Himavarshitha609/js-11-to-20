let fruits = ["Apple", "Orange", "Banana"];
delete fruits[1];
console.log(fruits); // ["Apple", <1 empty item>, "Banana"]
let fruits = ["Apple", "Orange", "Banana"];
let vegetables = ["Potato", "Tomato", "Onion"];
let food = fruits.concat(vegetables);
console.log(food); // ["Apple", "Orange", "Banana", "Potato", "Tomato", "Onion"]
let fruits = ["Apple", "Orange", "Banana"];
let food = fruits.concat("Pineapple");
console.log(food); // ["Apple", "Orange", "Banana", "Pineapple"]
let fruits = ["Apple", "Orange", "Banana"];
let food = fruits.concat("Pineapple", "Mango");
console.log(food); // ["Apple", "Orange", "Banana", "Pineapple", "Mango"]
let fruits = ["Banana", "Orange", "Apple"];
fruits.sort();
console.log(fruits); // ["Apple", "Banana", "Orange"]
let numbers = [40, 100, 1, 5, 29, 10, 2907];
numbers.sort();
console.log(numbers); // [1, 10, 100, 2907, 29, 40, 5]
let compare = (a, b) => {
    return a - b;
}
let numbers = [40, 100, 1, 5, 29, 10, 2907];
numbers.sort(compare);
console.log(numbers); // [1, 5, 10, 29, 40, 100, 2907]
let fruits = ["Apple", "Orange", "Banana"];
fruits.reverse();
console.log(fruits); // ["Banana", "Orange", "Apple"]
let numbers = [40, 100, 1, 5, 29, 10, 2907];
numbers.reverse();
console.log(numbers); // [2907, 10, 29, 5, 1, 100, 40]
let fruits = ["Apple", "Orange", "Banana"];
let copy = fruits.slice();
console.log(copy); // ["Apple", "Orange", "Banana"]
let fruits = ["Apple", "Orange", "Banana"];
let copy = fruits.slice(0, 2);
console.log(copy); // ["Apple", "Orange"]
let fruits = ["Apple", "Orange", "Banana"];
fruits.splice(0, 1);
console.log(fruits); // ["Orange", "Banana"]
let fruits = ["Apple", "Orange", "Banana"];
let index = fruits.indexOf("Banana");
console.log(index); // 2
