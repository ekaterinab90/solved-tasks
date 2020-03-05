# Solved-Tasks
#### Count of positives / sum of negatives
```javascript
function countPositivesSumNegatives(input){
if (input == null || input.length < 1){
  return [];
}
 let count = 0;
   let sum = 0;
     for(let i = 0; i < input.length; i++){
       if(input[i] > 0){
          count++;
  }   if(input[i] < 0) {
        sum = sum + input[i]
  }
  }
  return [count, sum];
  }

```











