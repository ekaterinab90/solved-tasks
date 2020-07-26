# Solved-Tasks
####  Дан двухмерный массив. Найти количество строк, в которых есть отрицательные элементы

````javascript

function countLinesWithNegativeElements(arr){
let sum = 0;
for(let i = 0; i < arr.length; i++){
  for(let j = 0; j < arr[i].length; j++){
    if(arr[i][j] < 0){
      sum++;
      break;
    }

 }
}
return sum;
}
console.log(countLinesWithNegativeElements([[1,-1,1], [-2,-2,-2], [3,-3,3]]));


````
