let marks = {
  coco: 80,
  harry: 98,
  rohan: 75
}

for (let i = 0; i < Object.keys(marks).length; i++) {
  console.log("The marks of " + Object.keys(marks)[i] + " are " + marks[Object.keys(marks)[i]]);
}
let marks = {
  coco: 80,
  harry: 98,
  rohan: 75
}

for (let key in marks) {
  console.log("The marks of " + key + " are " + marks[key]);
}
let correctNumber = 9;
let guessedNumber = null
while (guessedNumber != correctNumber){
guessedNumber = prompt("Enter a number: ")
console.log("Try Again!");
}
console.log("congrats, youve guessed the number!")
let correctNumber = 9;
let guessedNumber = null
while (guessedNumber != correctNumber){
guessedNumber = prompt("Enter a number: ")
if (guessedNumber == correctNumber){
break;
}
console.log("Try Again!");
}
console.log("congrats, youve guessed the number!")
function findMean(num1, num2, num3, num4, num5) {
  let sum = num1 + num2 + num3 + num4 + num5;
  let mean = sum / 5;
  return mean;
}

let result = findMean(10, 20, 30, 40, 50);
console.log("The mean of the numbers is " + result);
