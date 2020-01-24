# Solved-Tasks
#### Square Every Digit

````javascript
function squareDigits(num){
let a = num + '';
let str = '';
 for(let i =0; i < a.length; i++){
str = str +Math.pow(a[i],2);
 }
  return Number(str);
 }

````


