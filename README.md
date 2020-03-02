# Solved-Tasks
#### Difference of Volumes of Cuboids
```javascript
function findDifference(a, b) {
  let y = 1;
  let x = 1;
  for(let i = 0; i < a.length,  i < b.length; i++){
  y *= a[i];
  x *= b[i];
  }
  return Math.abs(y - x);
}
```











