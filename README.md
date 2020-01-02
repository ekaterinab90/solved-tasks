# Solved-Tasks
####  Difference Of Squares
````javascript
function differenceOfSquares(n){
  let totalSquareOfTheSum  = 0;
  for ( let i =1; i <= n; i++){
  totalSquareOfTheSum +=i;
}
 let sumOfTheSquares = 0;
 for ( let k = 1; k <= n; k++){
 sumOfTheSquares += (k * k);
}
 return (totalSquareOfTheSum**2)- sumOfTheSquares;
}
}
````