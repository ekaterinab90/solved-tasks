# Solved-Tasks
#### Check that "All digits of a three-digit number are different"
````javascript
function areAllDigitsDifferent(num){
let str = String(num);
  if(str[0] !== str[1] && str[0]!== str[2] && str[1] !== str[2] && str[2] !== str[1])
  return true;
  else return false;
}

````




