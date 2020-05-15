# Solved-Tasks
####  Obtain an array of degrees from the given array
````javascript

const arr = [4, -2, 8,0, -4,1, 5, -1];
let arr2 = [];

for (let i = 0; i < arr.length; i++){
   if(arr[i] === 0) arr2.push('zero degrees');
  else
   if(arr[i] === 1)
    arr2.push( '1 degree above zero');
  else 
   if(arr[i] === -1)
    arr2.push('1 degree below zero');
  else
   if(arr[i] > 1)
    arr2.push(`${arr[i]} degrees above zero`);
  else
   if(arr[i] <= -2)
    arr2.push(`${Math.abs(arr[i])} degrees below zero`);
  
}
````


5

