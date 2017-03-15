1. Use <link> on <head> because when loading website, it will load from top to bottom.  We use <link> on <head> to connect library first.

2. on <form> we have 
<input>: it has type=“” we can use type = “text”, “password”,”button”, “submit”. name is name to send server.  value is first value.
select box:  name = “”
option: value =“” 
if use selected, this option will choice.
<select name= “demo”>
<option value=“op1” selected> OP1 </option>		
<option value=“op1”> OP1 </option>	
</select>
Radio Button
choose only 1 value.
<input type = “radio” name = “demo1” value=“a1”> A1
<input type = “radio” name = “demo1” value=“a2”> A2
Text area: to type a long text. 
Button: send data from form to server.
Label: modifỉe for input text, radio button

CSS: 	
1. class can reuse, on website can have more class has same name. priority = 10
id only 1 on website , priority = 100.
2. Float to format position for element. we can use float: left, right,none.
3. padding :used to generate space around content.
margin:	used to generate space around elements.
4. Redefine the width and height of the component.
5. z-index set up stacked order. 
z-index: value;
if value= none: auto setup
if value = int; setup by value.
if value = inherit: inheritance from sub component.
