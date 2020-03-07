# Solved-Tasks
#### Find the divisors!
````javascript
function divisors(x) {
arr = [];
 for (var i=2;i<x;i++){
  if (x % i === 0){
   arr.push(i);
        }
 } if (arr.length === 0) {
        return `${x} is prime`;
    } else {
        return arr;
    }
}

````








