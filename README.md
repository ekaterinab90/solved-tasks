# Solved-Tasks
####  Does the string contain the given character

````javascript
function iSymbInString(str, symb){
  let el;

  for(let i = 0; i < str.length; i++){
    if(str[i] === symb){
    el = true;
    break;

    } else {
      el = false;
    }
  }
     return el;
  }
````


5

