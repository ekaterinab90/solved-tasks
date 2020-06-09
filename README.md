# Solved-Tasks
#### Draw Stairs


````javascript
let nrOfRows = 7;
 let str = '';
   for(let rowNumber = 1; rowNumber <= nrOfRows; rowNumber++){// outer loop handles nr of rows; rowNumber = each line increases by 2 stars
       str = str +  '-'.repeat(rowNumber - 1) + '#'.repeat(1); 
     str = (rowNumber === nrOfRows) ?  str : str + '\n';
 }
console.log(str);
#
-#;
--#;
---#;
----#;
-----#;
------#

````



