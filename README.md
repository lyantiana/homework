# homework 
Модуль 10
Задача 1
const result = +prompt("Please enter sign");
typeof result
if (result % 2 === 0) {
  console.log("четное")
} else if (isNaN(result)) {
  console.log("Упс, кажется вы ошиблись")
} else if (typeof result !== "number") {
  console.log("упс")
} else {
  console.log("нечетное")
}

Задача 2
const x = 1;
if (typeof x === "number") {
  console.log("x-число")
} else if (typeof x === "string") {
  console.log("x-строка")
} else if (typeof x === "boolean") {
  console.log("x-логический тип")
} else {
  console.log("Тип x не определен")
}

Задача 3
const str = 'Hello';
const splitStr = str.split('');
const reverseStr = splitStr.reverse();
const joinStr = reverseStr.join('');
console.log(joinStr);

Задача 4 
const res = Math.round(Math.random()*101);
console.log(res);

Задача 5 
const arr = [1, 2, 3];
console.log(arr.length);
const newArr = arr.map(function(item, index, array) {
  return item;
});
console.log(newArr);


