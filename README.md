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
```
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
```



## OUTPUT
![ss1](https://github.com/Harinikrishnamoorthy14/Ex07_Web-Design/assets/127816514/173cbf17-15b7-4079-b011-814a5ea3d34a)
![ss2](https://github.com/Harinikrishnamoorthy14/Ex07_Web-Design/assets/127816514/50813f01-4cbe-4bfe-b3eb-5c055368ed28)
![ss3](https://github.com/Harinikrishnamoorthy14/Ex07_Web-Design/assets/127816514/89bf0482-16d2-4718-9820-3fafef44deaf)
![ss4](https://github.com/Harinikrishnamoorthy14/Ex07_Web-Design/assets/127816514/a87854fa-2b03-40f4-b31d-be31582c54ba)
![ss5](https://github.com/Harinikrishnamoorthy14/Ex07_Web-Design/assets/127816514/4225a09f-5e08-4159-a82e-df31dc760c6a)


## RESULT
  
mplementation of a Simple Calculator using JavaScript is done successfully.
