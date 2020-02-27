# Solved-Tasks
#### Difference Of Squares

````javascript
function differenceOfSquares(n){
 let sum = 0;
 let sumSq = 0;
    for(let i = 0; i <= n; i++){
    sum += i;
    sumSq += i*i;
 }
    sum = sum * sum;
    return sum - sumSq;
}


````


