# Solved-Tasks
####  Sum of Multiples
```javascript
function sumMul(n,m){
  let sum = 0;
   if (n < 1 || m < 1) return "INVALID";
  for(let i = n; i <= m; i += n){
   sum += i;
  }
  return sum;
  }


```


