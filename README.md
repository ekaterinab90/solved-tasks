# Solved-Tasks
#### Find the Difference in Age between Oldest and Youngest Family Members

````javascript
function differenceInAges(ages){
 let youngest = ages[0];
 let older = ages[0];
  for(let i =0; i < ages.length; i++){
   if(older < ages[i]) older = ages[i];
    else if (youngest > ages[i]) youngest = ages[i];
  }
  return [youngest,older, older - youngest]
}
````




