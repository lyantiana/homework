# homework
const result = +prompt("Please enter sign");
if (result % 2 === 0) {
  console.log('четное')
} else if (isNaN(result)){
  console.log('Упс, кажется вы ошиблись')
} else {
  console.log('нечетное')
}

