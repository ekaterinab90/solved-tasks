# Solved-Tasks
#### Array plus array

````javascript
function arrayPlusArray(arr1, arr2) {
let arr3 = arr1.concat(arr2);
let counter = 0;
for ( let i = 0; i < arr3.length; i++){
counter = counter + arr3[i];
}
 return counter;
}
````


