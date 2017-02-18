# Sandbox
<!doctype html>
<html>
<head>  <title>loops, conditional statements, functions, variables, paramaters, arrays sandbox code example</title>  
<script>

//Sandboxing loops    
//Happy path - loop    
var coin;  
for (coin=1; coin < 5; coin++;){    
console.log(coin)
}
//Result - writen to the console

//Nasty path - bad syntax    
var coin;
for (coin=1; coin < 5; coin+1;){
console.log(coin)
}
//Result - loop will not loop    

//Nasty path - missing braces    
var coin;    
for (coin=1; coin < 5; coin++;)
console.log(coin)
//Result - loop will not work

//Happy path - do...while    
var weekdays = 0;
do {
  weekdays += 1;
  console.log(weekdays);
  } while (weekdays < 5);
//Result - loop will run five times  

//Happy path - for loop with array    
var numNums = [6, 4, 3, 0, 8, 2];    
for (var i = 0; i < 6; i++;){

}
//Result - loop will run through the numbers in the array

//Nasty path - using wrong index in an array
var nums = [98, 7, 34, 5, 7];
var firstArrayNum = nums[1];
//Result - firstArrayNum contains the number 7 instead of 98

  </script>

  <style>
  </style>
  </head>
<body> <p></p></body></html>
