# Solved-Tasks
####  Two to One
###### Take 2 strings s1 and s2 including only letters from ato z. Return a new sorted string, the longest possible, containing distinct letters,
   
   each taken only once - coming from s1 or s2.


````javascript

function longest(s1, s2) {  
  return [...(new Set(s1 + s2))].sort().join('');
}


function longest(s1, s2) {
  const nonD = (s1 + s2);
  let res = nonD.split('');
  let str = res.filter((el,i) => i === res.indexOf(el));
  return str.sort().join("");
}


````
