# Solved-Tasks
#### Calculate Two People's Individual Ages
````javascript
function getAges(sum,difference){

if(sum < 0 || difference < 0 || sum < difference){
return null;
}
let arr = [];
arr.push((sum+difference)/2,(sum-difference)/2)
return arr;
}

````

                             








