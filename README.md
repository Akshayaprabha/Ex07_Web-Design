# Ex.07 JavaScript - Simple Calculator
## AIM
  To write a program in JavaScript for implementing a simple calculator.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to implement the simple calculator.

### STEP-3
  Using branching statements to find the corresponding operation.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
~~~
<html>
<head>
<script type="text/javascript">
function calc()
{
var a=prompt("Enter 1st Value");
var b=prompt("Enter 2st Value");
var op=prompt("Enter Operation to Perform 1.Addition 2.Subtraction 3.Multiplication 4.Division");
var d;
if(op==1)
{
d=a+b;
alert(d);
}
else if(op==2)
{
d=a-b;
alert(d);
}
else if(op==3)
{
d=a*b;
alert(d);
}
else if(op==4)
{
d=a/b;
alert(d);
}
else
{
alert("Invalid Operation");
}
}
</script>
</head>
<body onload="calc()">
<h1>
Simple Calculator
</h1>
<hr color="red">
<p> 
Enter option for doing the corresponding operation
</p>
</body>
</html>
~~~

## OUTPUT
![aks1](https://github.com/Akshayaprabha/Ex07_Web-Design/assets/127816387/a0e9c269-c64a-41b1-9deb-f3b9e97039af)

![aks2](https://github.com/Akshayaprabha/Ex07_Web-Design/assets/127816387/ed1ff767-8dc9-4ea0-81d7-b2c7dd443aa1)

![aks3](https://github.com/Akshayaprabha/Ex07_Web-Design/assets/127816387/90385200-7dff-482d-a12b-1dd12f5a084e)
![aks4](https://github.com/Akshayaprabha/Ex07_Web-Design/assets/127816387/adf7821a-ef01-41b9-80c3-695be7409923)


## RESULT!!

  Implementation of a Simple Calculator using JavaScript is done successfully.
