# Solved-Tasks
#### Check how many of the numbers in the array are whole numbers

````javascript
const arr = [3, -6 ,7.01, 5, 21, 7.1, 2, 4, 4];
let count = 0;
for (let i = 0; i < arr.length; i++){
if( Number.isInteger(arr[i])){
  count++;
 }
}
````




