# Solved-Tasks
#### Find the Slope
````javascript
function slope(points)
{ 
  let x = points[2] - points[0];
  let y = points[3] - points[1];
  let div = y / x;
  return isFinite(div) ? div.toString() : "undefined"
}
````








