# Solved-Tasks
#### Is there a fourth floor in a Japanese house?
Одной из самых несчастливых цифр японцы считают цифру «4» (四). В больнице нет палат с таким номером, в домах предпочитают исключать 4-й этаж (за третьим следует пятый).

Напишите функцию с именем floorNumber, которая принимает число floor (номер этажа в доме) и число amount (количество этажей в доме) в качестве аргументов и возвращает:

true, если этаж с номером floor есть в доме,
false, если этажа с номером floor в доме нет.

Примеры: В 4-х этажном доме есть этажи с номерами 1, 2, 3, 5.

функция floorNumber(1, 4) должна возвратить true;
функция floorNumber(2, 4) должна возвратить true;
функция floorNumber(3, 4) должна возвратить true;
функция floorNumber(4, 4) должна возвратить false;
функция floorNumber(5, 4) должна возвратить true;
функция floorNumber(6, 4) должна возвратить false
````javascript
function floorNumber(floor, amount){
 if(floor !== 4  && floor <= (amount+1) ) return true;
 else return false;
}

````




