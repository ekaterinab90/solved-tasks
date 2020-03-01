# Solved-Tasks
#### Unique In Order
````javascript
var uniqueInOrder=function(iterable){
if(iterable === '') return [];
let arr = [];
arr.push(iterable[0]);
for(let i = 1; i < iterable.length; i++){
if(iterable[i] !== iterable[i - 1])
 arr.push(iterable[i]);
 }
 return arr;
} 

````



