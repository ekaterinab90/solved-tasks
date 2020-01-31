# Solved-Tasks
#### To square(root) or not to square(root)

````javascript
function squareOrSquareRoot(array) { 
 return array.map(i => {
  if(Number.isInteger(Math.sqrt(i))){
     return Math.sqrt(i)
   }else{
     return Math.pow(i,2);
   }
 })
}
````


