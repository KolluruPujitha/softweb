![Screenshot 2024-05-07 192801](https://github.com/KolluruPujitha/softweb/assets/150231340/5b51c702-7254-4d46-ad20-98242cd3883b)# Ex.07 Software Product Company Website
## Date:7-05-2024

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
home.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Softweb Home</title>
    <style>
        *{
            margin:0;
            padding:0;
        }
        #nav{
            background-color:wheat;
            color:#c035ea;
            padding: 15px;
    
        }
        li,h1,ul{
            display:inline;
        }
        ul{
            margin-left:25%;
        }
        a{
            color:blue;
            text-decoration: none;
        }
        a:hover{
            color:rgb(255, 255, 252);
            cursor:pointer;
 }
        input{
            width: 60%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
      
        .box {
    display: block;
    border-style: solid;
    border-radius: 20px;
    border-color: rgb(75, 20, 195);
    width: 400px;
    min-height: 300px;
    font-size: 20px;
    background-color:lightpink;
    margin: 0 auto; 
    text-align: center;
}

        .heading1{
            color:#237ba0;
            text-align: center;
            padding-top: 20px;
        }
        .heading2{
            color:violet;
            text-align: justify;
            font-size: 20px;
            margin: 50px auto 20px;
            width:80%
        }
        .edge{
            padding-left: 400px;
        }
        .box{
            text-align: center;
        }
 p{
            color:#000000;
            text-align: center;
        }
    
        .bottomdiv{
 background-color:lightgreen;
            color:black;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 105px;

        }
        table{
            margin-left: 40px;
        }
    </style>
</head>
<body background="backk.png">
    <div class="header">
        <nav id="nav">
            <h1>
                Dell software Solutions
            </h1>
                <ul>
                    <li class="li1"> 
                        <a href="home.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="product.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="people.html" target="_blank">People  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contact.html" target="_blank">Contact</a>
                    </li>
                </ul>
        </nav>
    </div>
    <div class="searchbar">
    <input placeholder="search">
    </div>
        <div><pre class="heading2"><i><b>
" Do You have a problem you can find your solution here."<b></i></pre></div>
        <div class="center">
            <div class="box">
            <h1 class="heading1">LOGIN HERE</h1>
            <br>
            <br>
            <form>
                <table cellpadding="10px" cellspacing="15px">
                    <tr>
                        <td>
                           <p> Username:</p>
                        </td>
                        <td>
                            <input type="email" name="name" placeholder="Enter a Email">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <p> Password:</p>
                        </td>
                        <td>
                            <input type="password" name="pwd" placeholder="Enter a Password">
                        </td>
                    </tr>
                    <tr>
                        <td colspan="2">
                            <input type="submit" value="LOGIN" style="background-color: rgb(128, 28, 223); color:white;">
                        </td>
                    </tr>
                </table>
                
            </form>
            </div>
        </div>
    <div class="bottomdiv">
        <p> Copyrights @2024 and Developed kolluru pujitha(212223240074)
</body>
<html>
```
product.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Softweb Products</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:wheat;
            color:lavender;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:45%
        }
        li{
            color:wheat;
        }
        li:hover{
            color:white;
            cursor:pointer;
        }
 input{
            width: 18%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
        .box{
            border-color:wheat;
            border-width:2px;
            border-style:solid;
            display: inline-block;
            width: 414px;
        }
        .product{

            text-align: center;
        }
        .box{
            background-color:lightskyblue;
            cursor:pointer;
        }
        a{
            color:#062d41;
            text-decoration: none;
        }
        a:hover{
            color:white;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:black;
        }
      p{
            color:lightcoral;
            text-align: center;
        }
   b{
            width: 300px;
            height: 200px;
        }
    h1{
            color:black;
            text-align: center;
        }
        .bottomdiv{
 background-color:violet;
            color:black;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 230px;

        }
    </style>
</head>
<body background="backk.png">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">DSS</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="product.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="people.html" target="_blank">People  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contact.html" target="_blank">Contact</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">PRODUCTS</h1>
        <br>
        <div class="product">
            <div class="box">
               <b><img src="python.jpeg" ></b>
                <h1>PYTHON</h1>
                <p>
                   
            Learn python from scratch and we also teach you additional frameworks</p>
            </div>
            <div class="box">
                <img src="c pr.png">
                <h1>Introduction to C</h1>
                <p>Learn C Language and it's Functions </p>
            </div>
            <div class="box">
                <img src="html.jpeg">
                <h1>HTML</h1>
                <p>Learn HTML and and how to design web pages in an effective way</p>
            </div>
            <div class="box">
                <img src="java.jpeg">
                <h1>JAVA</h1>
                <p>Learn Java and Concepts such as abstraction,encapsulation,inheritance and polymorphism</p>
        </div>
    </div>
    <div class="bottomdiv">
        <b>Copyrights @2024 and Developed by kolluru pujitha</b>
    </div>
</body>
</html>
```
people.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Softweb Members</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:wheat;
            color:#000000;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:45%
        }
        li{
            color:lightblue;
        }
        li:hover{
            color:#fafafa;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
        a{
            color:teal;
text-decoration: none;
        }
        a:hover{
            color:#d01ba3;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:#63c071;
        }
        .bottomdiv{
            background-color:lavender;
            color:black;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 0.7px;

        }
        img{
            border-radius: 50%;
            width: 200px;
            display: inline;
            padding:15px;
            
        }
        .person{
            margin: 150px;
            text-align: center;
        }
        b,p{
            color:black;
            text-align: center;
        }
      
</style>
</head>
<body>
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">DSS</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="product.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="people.html" target="_blank">People  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contact.html" target="_blank">Contact</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">Members</h1>
        <table class="person">
            <tr>
                <td>
                    <img src="dhoni.jpeg" width="100" height="160">
                </td>
		

                <td>
                    <img src="prabhas.jpeg" width="100" height="160">
                </td>
		
                <td>
                   <img src="sushant singh.jpeg" width="100" height="160">
                </td>
                <td>
                    <img src="nani.jpeg" width="100" height="160" >
                </td>
                <td>
                    <img src="alluarjun.jpeg" width="100" height="160">
                </td>
            </tr>
            <tr>
                <td>
                    <b>MS Dhoni</b>
                    <p>Director</p>
                </td>
                <td>
                    <b>Prabhas</b>
                    <p>CEO,Founder</p>
                </td>
                <td>
                    <b>Sushanth</b>
                    <p>Co-Founder</p>
                </td>
                <td>
                    <b>Nani</b>
                    <p>Asst.Director</p>
                </td>
                <td>
                    <b>Allu alluarjun</b>
                    <p>Marketing Director</p>
                </td>
              
            </tr>
        </table>
    </div>
    <div class="bottomdiv">
<p>Copyrights @2024 and Developed by kolluru pujitha</p>
    </div>
</body>
</html>
```
contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Softweb contact</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:rgb(125, 166, 198);
            color:#000000;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:45%
        }
        li{
            color:#074565;
  }
        li:hover{
            color:white;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
        .box{
            border-color:rgb(254, 253, 253);
            border-width:2px;
            border-style:solid;
            display: inline-block;
            width: 414px;
        }
        .product{

            text-align: center;
        }
        .box{
            background-color:rgb(66, 16, 66);
            cursor:pointer;
        }
        a{
            color:b#007cb9;
            text-decoration: none;
        }
        a:hover{
color:rgb(255, 255, 255);
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:#10c000;
        }
        .table1{
            color:rgb(97, 0, 100);
            font-size: large;
        }
        .contact{
            margin-left:400px;
        }
        .heading3{
            padding-top: 30px;
            padding-bottom: 10px;
            text-align: center;
            color:#a8e15e;
        }
        .table2{
            color:#000000;
            font-size: large;
            background-color:rgb(187, 208, 219);
            border-radius: 5px;
            border-style:dotted;
            border-color: rgb(125, 199, 213);

        }
        .queries{
            margin-left:400px;
        }
        .bottomdiv{
            background-color:rgb(243, 39, 162);
            color:#000000;
            text-align: center;
            position:relative;
display:block;
            margin-top: 24px;

        }
    </style>
</head>
<body background="backk.png">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">DSS</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="product.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="people.html" target="_blank">People  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contact.html" target="_blank">Contact</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">CONTACT US</h1>
        <div class="contact">
            <table cellpadding="15px" cellspacing="15px" class="table1">
                <tr>
                    <td>
                        ADDRESS :
                    </td>
                    
                    <td>
                        t nagar,chennai,602105
</td>
                </tr>
                <tr>
                    <td>
                        LANDMARK :
                    </td>
                    <td>
                        Near chennai Public school
                    </td>
                </tr>
                <tr>
                    <td>
                        EMAIL :
                    </td>
                    <td>
                        dell@gmail.com
                    </td>
                </tr>
                <tr>
                    <td>
                        PHONE :
                    </td>
                    <td>
                        9988882390
                    </td>
                </tr>
            </table>
        </div>
        <div>
            <h2 class="heading3">QUERIES</h2>
            <div class="queries">
                <table cellpadding="15px" cellspacing="15px" class="table2">
                    <tr>
                        <td>
 NAME :
                        </td>
                        <td>
                            <input type="name" placeholder="Enter your name"> 
                        </td>
                    </tr>
                    <tr>
                        <td>
                            EMAIL :
                        </td>
                        <td>
                            <input type="email" placeholder="Enter your E-mail">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            Your Query :
                        </td>
                        <td>
                            <input type="text" placeholder="Enter your Queries">
                        </td>
                    </tr>
                    <tr>
                        <td colspan="2">
                            <input type="submit" style="background-color: rgb(214, 160, 25); color:#000000;">
                        </td>
                    </tr>
            </table>
        </div>
        <div class="bottomdiv">
            <p>Copyrights @2024 and Developed by kolluru pujitha(212223240074)</p>
        </div>
    </div>
</body>
</html>
```
## OUTPUT:
![Screenshot 2024-05-07 192747](https://github.com/KolluruPujitha/softweb/assets/150231340/5a9857a5-3b33-4135-986f-efcc8d340306)
![Screenshot 2024-05-07 192801](https://github.com/KolluruPujitha/softweb/assets/150231340/c26482d3-856c-49a8-b1bf-ba20add42804)

![Screenshot 2024-05-07 192813](https://github.com/KolluruPujitha/softweb/assets/150231340/2f3c5c68-e93a-4055-b549-2ce7b14d19bf)
![Screenshot 2024-05-07 192826](https://github.com/KolluruPujitha/softweb/assets/150231340/455450a2-429f-417b-8774-7583d47ee9be)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
