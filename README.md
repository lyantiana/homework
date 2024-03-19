# homework 
10.3
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

