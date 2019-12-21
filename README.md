# Solved-Tasks
#### Discover The Original Price
````javascript
function discoverOriginalPrice(discountedPrice, salePercentage){
 let x = discountedPrice /  (100 - salePercentage) *(100);
 return +x.toFixed(2);
}
````











