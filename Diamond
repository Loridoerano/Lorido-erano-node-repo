let x = 10;
console.log(x);
let i = 1;
let l;
let n = 0;

const spaces = '   '; 
const  star = ' * ';

//loop
while(i <= x) {
  l = (x - i)/2;
  console.log(spaces.repeat(l) + star.repeat(i));
  i = i + 2;
}

while(i >= 2) {
  i = i - 2;
  l = (x - i)/2;
  if (i < x) {                       
    console.log(spaces.repeat(l) + star.repeat(i));
  } else { 
    continue; 
    }
}

//check if x is odd or even
let E;
 function isOddOrEven(numberToCheck) {
 const isOdd = numberToCheck % 2 != 0;
   //print message and number
 if (isOdd) return console.log(`The number of Star ${numberToCheck} is odd`);
 else return console.log(`The number of Star ${numberToCheck} is even`);

   return console.log(`The number of Star ${numberToCheck} is ${numberToCheck % 2 != 0 ? "odd" : "even"}.`)
 }

 isOddOrEven(x);
