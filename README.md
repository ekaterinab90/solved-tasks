# Solved-Tasks
#### Find the number of array elements whose last digit is 0.
````javascript
const ar = [1, -9, 0, -8, 50, -20, -5, 7, 9, 11];
let res = 0;
for (let i = 0; i < ar.length; i++){
  if (ar[i] % 3 === 0) {
    res++;
  }
}

````








