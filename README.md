# Solved-Tasks
#### Divide and Conquer
````javascript
function divCon(x){
 let str = 0;
 let num = 0;
 for(let i = 0; i < x.length; i++){
   if( typeof x[i] === 'number'){
     num += x[i];         
   }
   if(typeof x[i] === 'string'){
     str += (+x[i]);
    }
   }
     return num - str; 
 }

````








