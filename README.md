# Solved-Tasks
####  No zeros for heros
`````javascript
function noBoringZeros(n) {
let a = n + "";
return Number(a.replace(/0+$/g, '')); 
}

`````
