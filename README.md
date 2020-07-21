# Solved-Tasks
#### Digit triangle in ascending order

````javascript

let n = 5;
  let str = '';
let count = 1;
for (let i = 1; i <= n; i++) {   // displays the number of rows
  for (let j = 1; j <= i; j++) { // j display the number of digits in a row: 
    if(j < i) str += count + ' '; // daca j ii mai mic ca i o sa se adauge empty space between digits
    else str += count; // in caz contrar nu, deci la sfirsit de rand nu o sa fie empty space
   count++; //dupa fiecare adaugare in randul anterior count o sa se mareasca cu 1 si asa avem un sequence de numere
  }
  str = (n == i) ? str : str + '\n'
}
 console.log(str);


````
