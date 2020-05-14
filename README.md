# Solved-Tasks
#### Count the number of valid names( names >= 5 letters). If the name contains less than 5 letters - add the underscore (_) sign so that the names will become valid (names === 5 letters)
````javascript
let arr = ['Jannine', 'Erika','Ann', 'Cassandra', 'Jonathan','R', 'Alfred', 'Sara', 'Eva'];
let count = 0;
for (let i = 0; i < arr.length; i++){
   if(arr[i].length >= 5){
     count++; // count will count the names with >= 5 letters
   }else{   // else will work for the names with less than 5 letters
     for (let j = arr[i].length; j < 5; j++){ //this loop will work for missing letters in names,and will add to the missing name.length the required number of "_"
     arr[i] = arr[i] + '_'
    }
  }
}

````




