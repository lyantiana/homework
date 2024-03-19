# homework
const result = +prompt("Please enter sign");
typeof result
if (result % 2 === 0) {
  console.log("четное")
} else if (isNaN(result)){
  console.log("Упс, кажется вы ошиблись")
} else if (typeof result !== "number"){
  console.log("упс")
} else {
  console.log("нечетное")
}

