# Solved-Tasks
#### Tortoise racing
````javascript
function race(v1, v2, g) {
if(v1 > v2) return null;
 let t = g /(v2-v1); // time in hour
 let time = t * 3600; //sec
 let hour = Math.trunc(time / 3600);
 let min = Math.trunc((time - hour * 3600)/ 60); // minutes
 let sec =  Math.trunc(time - hour * 3600 - min * 60);
 return [hour, min, sec]
} 

````


