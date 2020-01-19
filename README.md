# Solved-Tasks
####  Filter the number
````javascript
let FilterString = function(value){
let a = /\d+/g;
let b = value.match(a).join([]);
return +b;
}
````


