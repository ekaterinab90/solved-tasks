# Solved-Tasks
#### Training JS #10: loop statement --for
````javascript
function pickIt(arr){
  let odd=[],even=[];
  for(let i = 0; i < arr.length; ++i){
  if(arr[i] % 2 === 0)
  even.push(arr[i]);
  else odd.push(arr[i]);
}
return [odd,even];
}


````


