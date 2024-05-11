# Ex.08 Design of a Standard Calculator
## Date: 08-04-2024

## AIM:
To design a web application for a standard calculator with minimum five operations.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for creating attractive colors.

### Step 4:
Write JavaScript program for implementing five different operations.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :

~~~
calc.html

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script type="text/javascript">
    function dis(x){
        document.getElementById("inbox").value+=x;
    }
    function clr(){
        document.getElementById("inbox").value='';
    }
    function del(){
        var num=document.getElementById("inbox").value;
        var ans=num.substring(0,num.length-1);
        document.getElementById("inbox").value=ans;
    }
    function fun(){
        var res=document.getElementById("inbox").value;
        if(res){
        var ans=eval(res);
        document.getElementById("inbox").value=ans;
        }
    }
    </script>

</head>
<style>
body{
background-color: peachpuff;
}
.container{
 position:relative;
margin-top:30px;
margin-left:45px;
width:270px;
height:380px;

}
button{
width:60px;
height:50px;
padding:20px 40px 20px 20px;
border-right: none;
font-size:20px;
text-align: center;
}
input{

width:260px;
height:100px;
font-size:30px;}
#b10{
padding-right:107px;
}
.box{
    position:absolute;
    top:27%;
margin-left:35%;
   height:430px;
   width:340px;
    background-color:hsla(268, 73%, 48%, 0.304);
    margin-right: 100px;
    
top: 30%;
left: 60px;
border-radius: 10px;
overflow: hidden;
padding-right: 5px;
}
h2{
    text-align: center;
    color: #5100ff;
    font-family:serif;
    margin-top: 90px;
    margin-left:0.5%;
    font-size: x-large;
}
.red{
    color: green;
}
.red1{
    color: green;
}
.red3{
    color: green;
}
.red4{
    color: green;
}
.red5{
    color: green;
}
.yellow{
    color: green;
}
.yellow2{
    color: green;
    
}
.red6{
    color: green;
}
.blue{
    color: blue;
    background-color: rgba(135, 250, 242, 0.603);
}
</style>
</head>
<body>
<div class="box">
<div class="container">
<input type="text"  class="blue" id="inbox"name="input"><br>
<button onclick="clr()"> AC</button>
<button class="red"  onclick="del()">DE</button>
<button class="red4" onclick="dis('%')">%</button>
<button class="red5" onclick="dis('/')">/</button><br>
<button name="1" onclick="dis('1')">1</button>
<button onclick="dis('2')">2</button>
<button onclick="dis('3')">3</button>
<button class="red3" onclick="dis('+')">+</button ><br>
<button onclick="dis('4')">4</button>
<button  onclick="dis('5')">5</button>
<button onclick="dis('6')">6</button>
<button class="red2"  onclick="dis('-')">-</button><br>
<button onclick="dis('7')">7</button>
<button onclick="dis('8')">8</button>
<button onclick="dis('9')">9</button>
<button class="yellow" onclick="dis('*')" >x</button><br>
<button class="yellow1" onclick="dis('.')">.</button>
<button onclick="dis('0')">0</button>
<button id="b10" class="red6" onclick="fun()">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;=</button><br>
</div>
</div>
<h2>
    Calculator <br><br>
    Varsha  A (212223220121) <br>
    
</h2>
</body>
</html>

~~~

## OUTPUT:

![Screenshot 2024-04-28 142136](https://github.com/04Varsha/Calc/assets/149035374/b2c0e8ff-07dd-4811-a099-9410e9534600)

![Screenshot 2024-04-28 150554](https://github.com/04Varsha/Calc/assets/149035374/34085fb3-7832-4fea-8a9f-4c8f89ca2b25)

![Screenshot 2024-04-28 150603](https://github.com/04Varsha/Calc/assets/149035374/d1015da9-b1a5-4bb9-b775-3fda75c5111d)

## RESULT:
The program for designing a standard calculator using HTML and CSS is executed successfully.
