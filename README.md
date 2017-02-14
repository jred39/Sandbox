# Sandbox
<!doctype html>
<html>
<head>  <title>math sandbox code example</title>  
<script>     //Sandboxing Math functions    
//Sandboxing square root    
//Happy path - loop    
var pill;  
for (pill=1; pill < 5; pill++;)    
console.log(pill)    
//Result -  writen to the console

//Nasty path - negative number    
root = Math.sqrt(-10)    
console.log(root)    
//Result - NaN (Not a Number) written to console    

//Nasty path - string    
root = Math.sqrt("hello")    
console.log(root)    
//Result - NaN written to console

//Nasty path - empty string    
root = Math.sqrt("")    
console.log(root)    
//Result - 0 written to console    

//Nasty path - null    
root = Math.sqrt(null)    
console.log(root)    
//Result - 0 written to console

//Sandboxing absolute value    
//Happy path - absolute value of a negative number    
var absValue = Math.abs(-100)    
console.log(absValue)    
//Result - 100 written to console    

//Nasty path - positive value    
absValue = Math.abs(21)    
console.log(absValue)    
//Result - 21 written to console    

//Nasty path - string    
absValue = Math.abs("hello")    
console.log(absValue)    
//Result - NaN written to console    

//Nasty path - empty string    
absValue = Math.abs("")    
console.log(absValue)    
//Result - 0 written to console    

//Nasty path - null    
absValue = Math.abs(null)    
console.log(absValue)    
//Result - 0 written to console  </script>

  <style>
  </style></head>
<body> <p>Open the console of your browser to see the results.</p></body></html>
