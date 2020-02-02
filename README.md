# Solved-Tasks
#### Find the next perfect square!

````javascript
function findNextSquare(sq) {
 if(Math.sqrt(sq) % 1 === 0){
   do {
     sq++;
   }while (Math.sqrt(sq) % 1 !==0)
     return sq;
   }else{
     return -1;
  }
 }
````


