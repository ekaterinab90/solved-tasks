# Solved-Tasks
####  Get an array of integers from 1 to n, except for the given number x.


````javascript
function fillArray(n, x){
  let arr = [];
  
  for(let i = 1; i <= n; i++){
    if(i === x) continue;
    arr.push(i);
  }
    return arr;
  } 
````


5

