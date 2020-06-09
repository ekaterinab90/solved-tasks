# Solved-Tasks
#### Draw Pyramid


````javascript
let nrOfRows = 5;
 let str = '';
   for(let rowNumber = 1; rowNumber <= nrOfRows; rowNumber+= 2){// outer loop handles nr of rows; rowNumber = each line increases by 2 stars
     str = str +  ' '.repeat((nrOfRows - rowNumber )/2) + '*'.repeat(rowNumber);
     str = (rowNumber === nrOfRows) ?  str : str + '\n';
 }
console.log(str);

````



