# Solved-Tasks
#### Is it a palindrome?
````javascript
function isPalindrome(x) {
  x = x.toLowerCase();
  let reverse = '';
  for(let i = x.length - 1; i >= 0; i--){
  reverse = reverse + x[i]
  }
  return reverse == x;
}
 
````


