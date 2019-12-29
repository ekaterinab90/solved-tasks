# Solved-Tasks
####  101 Dalmatians - squash the bugs, not the dogs!
````javascript
function howManyDalmatians(number){
    var dogs = ["Hardly any", "More than a handful!", "Woah that's a lot of dogs!", "101 DALMATIANS!!!"];
  return (number <= 10) ? dogs[0]: (number <= 50 && number > 10) ? dogs[1] : (number > 50 && number <=100) ? dogs[2] :dogs[3];
}

````