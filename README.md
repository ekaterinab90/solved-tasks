# Solved-Tasks
####  How old will I be in 2099?
````javascript
function  calculateAge( yearBorn,yearsNow ){
  let  a = yearBorn - yearsNow;
  let b = yearsNow - yearBorn;
  if (yearBorn <  yearsNow && b === 1){
  return "You are 1 year old.";

  }if(yearBorn === yearsNow){
return "You were born this very year!";
} if ( yearBorn < yearsNow){
 return `You are ${yearsNow - yearBorn} years old.` ;
   
} if( yearBorn > yearsNow && a > 1){
 return `You will be born in ${yearBorn - yearsNow} years.`;
}if (yearBorn <  yearsNow && b === 1){
  return `You will be born in ${a} year.`;

} if(yearBorn > yearsNow && a === 1){
  return  'You will be born in 1 year.';
}
}

````