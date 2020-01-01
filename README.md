# Solved-Tasks
####  Twice as old
````javascript
function twiceAsOld(dadYearsOld, sonYearsOld) {
let a = sonYearsOld * 2;
 if(sonYearsOld === 0){
  return dadYearsOld;
}else{
  return Math.abs(dadYearsOld - a);
 }
 }

````