# Solved-Tasks
#### Check the truth of the statement "All three-digit numbers are sorted in increasing order.
````javascript
function areDigitsInAscendingOrder(num){
let str = String(num);
if(str[0] < str[1] && str[0] < str[2] && str[1] < str[2]) return true;
  else return false;
}

````




