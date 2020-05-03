# Solved-Tasks
#### Grasshopper - Debug(fahrenheit to celsius)
````javascript
//version 1
function weatherInfo (temp) {
 let celsius = (temp - 32) * (5/9);
  if (celsius <= 0)
    return (celsius + " is freezing temperature");
  else
    return (celsius + " is above freezing temperature")
}


// version 2
function weatherInfo (temp) {
 var c = (temp - 32) * (5/9);
 return c <= 0 ? c + " is freezing temperature" : c + " is above freezing temperature";}

//version 3
function weatherInfo (fahrenheit) {
  var celcius = convertToCelsius(fahrenheit);
  if (celcius <= 0) {
    return celcius + " is freezing temperature";
  }
  return celcius + " is above freezing temperature";
}
function convertToCelsius (fahrenheit) {
  return (fahrenheit - 32) * (5/9);
}
````




