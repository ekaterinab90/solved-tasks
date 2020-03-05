# Solved-Tasks
#### How good are you really?
````javascript
function betterThanAverage(classPoints, yourPoints){
 classPoints.push(yourPoints)
  let count = 0;
    for(let i = 0; i < classPoints.length; i++){
      count += classPoints[i]; 
 }
   return  count / classPoints.length > yourPoints ? false : true;
}
````











