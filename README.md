# calculator
<!DOCTYPE html>
<html lang="en">
<head>
<title>JavaScript calculator</title>
<style>
h1{
   text-align:center;
   padding:23px;
   background_color:skyblue;
   color:white;
  }
#clear{
width:270px;
border:3px solid gray;
border-radius:3px;
padding:20px;
}
input
{
width:20px;
background-color:green;
color:white;
border:3px solid gray;
border_radius:5px;
padding:26px;
margin:5px;
font-size:15px;
}
#calc{
width:250px;
border:5px solid black;
border_radius:3px;
padding:20px;
margin:auto;
}
</style>
</head>
<body>
<h1>calculator program in JavaScript</h1>
<div class="formstyle">
<form name="form1">
<!--This input box shows the button pressed by the user in calculator.-->
<input id="calc"type="text"name="answer"><br><br>
<!--Display the calculator button on the screen.-->
<!--onclick() function display the number presses by the user.-->
<input type="button" value="1" onclick="form1.answer.value+='1'">
<input type="button" value="2" onclick="form1.answer.value+='2'">
<input type="button" value="3" onclick="form1.answer.value+='3'">
<input type="button" value="+" onclick="form1.answer.value+='+'">
<br> <br>
<input type="button" value="4" onclick="form1.answer.value+='4'">
<input type="button" value="5" onclick="form1.answer.value+='5'">
<input type="button" value="6" onclick="form1.answer.value+='6'">
<input type="button" value="-" onclick="form1.answer.value+='-'">
<br> <br>
<input type="button" value="7" onclick="form1.answer.value+='7'">
<input type="button" value="8" onclick="form1.answer.value+='8'">
<input type="button" value="9" onclick="form1.answer.value+='9'">
<input type="button" value="*" onclick="form1.answer.value+='*'">
<br> <br>
<input type="button" value="/" onclick="form1.answer.value+='/'">
<input type="button" value="0" onclick="form1.answer.value+='0'">
<input type="button" value="." onclick="form1.answer.value+='.'">
<input type="button" value="="onclick="form1.answer.value=eval(form1.answer.value)">
<br>
<input type="button" value="clear all"onclick="form1.answer.value=''"id="clear">
<br>
</form>
</div>
</body>
<html>
