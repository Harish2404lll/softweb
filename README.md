# Ex.07 Software Product Company Website
## Date:

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
### Home:
```
<html lang="en">
<head>
    <title>Home Page</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="/static/CSS/styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #007bff;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
            text-transform: uppercase;
        }
```
Products:
```
<html lang="en">
<head>
    <title>Products</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <style>
        .home {
            background-color: cyan;
            padding: 20px;
        }

        .text {
            color: blueviolet;
            font-size: 30px;
        }

        .product-highlight {
            border: 1px solid #ccc;
            background-color: white;
            padding: 20px;
            text-align: center;
        }

        .product-highlight img {
            max-width: 100%;
        }

        .product-label {
            color: gold;
        }

        .bot {
            text-align: center;
            font-size: larger;
            color: magenta;
        }
    </style>
</head>
<body>
    <div class="container home">
        <header>
            <nav class="navbar navbar-expand-lg navbar-light bg-light">
                <a class="navbar-brand" href="#">Products</a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav">
                        <li class="nav-item active">
                            <a class="nav-link" href="home.html">Home</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="products.html">Products</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="people.html">People</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="contact.html">Contact Us</a>
                        </li>
                    </ul>
                </div>
            </nav>
        </header>

        <div class="text">
            <p>These are the products that are available now</p>
        </div>

        <div class="row">
            <div class="col-md-6">
                <div class="product-highlight">
                    <img src="/static/images/h.png" alt="HTML">
                    <div class="product-label l1"><p><b>HTML</b></p></div>
                </div>
            </div>
            <div class="col-md-6">
                <div class="product-highlight">
                    <img src="/static/images/css.png" alt="CSS">
                    <div class="product-label l2"><p><b>CSS</b></p></div>
                </div>
            </div>
        </div>

        <div class="row">
            <div class="col-md-6">
                <div class="product-highlight">
                    <img src="/static/images/apps.jpeg" alt="Web Software">
                    <div class="product-label l3"><p><b>Web Software</b></p></div>
                </div>
            </div>
            <div class="col-md-6">
                <div class="product-highlight">
                    <img src="/static/images/software.jpeg" alt="Product Development">
                    <div class="product-label l4"><p><b>Product Development</b></p></div>
                </div>
            </div>
        </div>

        <div class="bot">
            <p>To Order Online: Call 90 80 70 2009</p>
        </div>

        <div class="footer">
            <footer style="color:white">
                Copyright &copy; 2023 Developed by HARISH
            </footer>
        </div>
    </div>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
### People:
```
<html lang="en">
    <head>
        <title>
            People
        </title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/CSS/styles.css">
        <style>
        .home{
            height: 3000px;
            width: 85%;
            border: 12px solid red;
            padding-left:10px;
            padding-right:10px;
            margin-left: auto;
            margin-right:auto;
            background-color:cyan;
        }
        .text{
        color:blueviolet;
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
        
        }
        .content{
            border:2px solid green;
            background-color:rgb(119, 155, 153);
            width:98%;
            height:2690px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;
        }
        .ceoph{
            background-image: url(/static/images/a.jpg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:3px solid gold;
            height:300px;
            width:20%;
            position:relative;
            left: 0px;
            margin-left:auto;
            margin-right: auto;
        }
        .ceo{
            color: red;
            position:relative;
            text-align:center;
            
            
        }
        .manph1{
            background-image: url(/static/images/b.jpg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:300px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;            
        }
        .man1{
            color: red;
            position:relative;
            text-align:center;
            
        }
        .manph2{
            background-image: url(/static/images/c.jpg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:300px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .man2{
            color: red;
            position:relative;
            text-align:center;
        }
        
        .amph1{
            background-image: url(/static/images/d.jpg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:300px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am1{
            color: red;
            position:relative;
            text-align:center;
        }

        .amph2{
            background-image: url(/static/images/e.jpg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:220px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am2{
            color: red;
            position:relative;
            text-align:center;
        }
        

        </style>
    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: darkred; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: darkred; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:darkred; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:darkred; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>People</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p>Board Members</p>
                    <h4><u>Chairman</u></h4>
                    </div>
                    <div class="ceoph"></div>
                    <div class="ceo"><p align="center"><b><h2>JEFF_BEZOS</h2></b></div>
                    <br>
                    <div class="text">
                        <p><b><u>Head executives</u></b></p><br>
                    </div>
                    <div class="manph1"></div>
                    <div class="man1"><p align="center"><b><h2>ANDRY_JESSY</h2></b></p></div>
                    <div class="manph2"></div>
                    <div class="man2"><p><b><h2>OLSAVSKY</h2></b></p></div>
                    <br>
                    <div class="text"><p><b><u>Manager</u></b></p></div><br>
                    <div class="amph1"></div>
                    <div class="am1"><p align="center"><b><h2>REYNOLDS</h2></b></p></div>
                    

                    
                    <div class="am3"><p align="center"><b><h2></h2></b></p></div><br>
                    <div class="text">Quality code for reliable future!<br>!</div>
                </div>
                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2023 Developed by HARISH</footer></div>
            </div>
        </div>
    </body>
</html>
```
### Contact:
```
<html lang="en">
    <head>
        <title>
            Contact Us
        </title>
        <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/CSS/styles.css">
    <style>
    .text{
        color:rgb(103, 51, 153);
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
    }
    
    </style>

    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: rgb(113, 36, 36); text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: darkred; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:rgb(147, 68, 68); text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:darkred; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>Contact Us</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p><b>Here are the details about us
                    <h5>Do contact us for any need</h5></b></p>
                    
                    </div>
                    <b><h2>Contact Information:</h2></b>
                    <p><b>&emsp;&ensp;Address:</b>
                        anna nagar,chennai, TamilNadu, India.
                    </p>
                    <ul>
                        <li><b>Landline:</b> 12345678</li>
                        <li><b>Mobile</b>: 90 80 70 2009</li>
                        <li><b>Facebook</b>: fb/ragu</li>
                        <li><b>Email Id:</b>ragu@saveetha.com</li>
                    </ul>
                    <div style="text-align: center;color:rgb(198, 97, 198);font-size:20px;"><b>Use our services and Beautify Yourself!</b></div>

                </div>
                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2023 Developed by RAGUNATH</footer></div>
            </div>
        </div>
    </body>
</html>
home.html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Home Page
        </title>
        <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/CSS/styles.css">
    <style>
    .text{
        color:rgb(139, 76, 199);
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
    }
    img{
        height: 150px;
        width: 150px;
        align-items:center;
    }
    </style>

    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: darkred; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: darkred; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:darkred; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:darkred; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>LEO SOFTWARE COMPANY</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <marquee><b>Rasing Software Developer</b></marquee>
                    <p style="color:purple; font-family:'Tahoma'; font-size:20px;"> This is the Official Website of our Software company!</p>
                    </div>
                    <p>Leading software developer <span style="background-color:lime">Cognizant solutions</span>
                         GST Billing software | Supermarket software | Mobile shops | Restaurent management| And much more</p>
                    <br>
                <center>
                    <img src="/static/images/a.jpeg">
                    <img src="/static/images/b.jpeg">
                    <img src="/static/images/C.jpeg">
                    <img src="/static/images/d.jpg">
                    
                    
                </center>
                </div>
                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2023 Developed by charumathi</footer></div>
            </div>
        </div>
    </body>
</html>
```
### CSS:
```
STYLES .CSS



.home {
    height: auto;
    width: 85%;
    border: 2px solid lawngreen;
    padding: 10px;
    margin: 0 auto;
    background-color: rgb(149, 196, 196);
}

.content {
    border: 1px solid #ccc;
    background-color: white;
    width: 95%;
    height: auto;
    padding: 20px;
    margin: 0 auto;
}

.header {
    height: 128px;
    width: 100%;
    background-image: url(/static/images/header.png);
    background-size: cover;
    background-position: center;
}

.logo {
    height: 21%;
    width: 10%;
    position: absolute;
    background-image: url(/static/images/icon.png);
    background-size: cover;
}

.prod,
.people,
.contact,
.h {
    height: auto;
    width: auto;
    border: 2px solid transparent;
    text-align: center;
    padding: 15px;
    font-family: 'Algerian';
    font-size: large;
    display: inline;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.prod:hover,
.people:hover,
.contact:hover,
.h:hover {
    background-color: darkmagenta;
}

.prod,
.people,
.contact {
    margin-right: 20px;
}

.h {
    position: relative;
    top: 30px;
}

.footer {
    border: 2px solid gold;
    width: 98%;
    height: 6px;
    background-color: darkmagenta;
    text-align: center;
}

.title {
    border: 2px solid lawngreen;
    background-color: gold;
    padding: 10px;
    width: 100%;
    text-align: center;
    font-family: 'Algerian';
}

.content1 {
    border: 1px solid #ccc;
    background-color: white;
    width: 98%;
    padding: 20px;
    margin: 0 auto;
}
```

## OUTPUT:
![WhatsApp Image 2023-11-14 at 19 39 28_2ea0415b](https://github.com/Harish2404lll/softweb/assets/141472096/64c5cf4c-59ae-46e1-b123-46ef84861622)

![WhatsApp Image 2023-11-14 at 19 40 10_b86324dc](https://github.com/Harish2404lll/softweb/assets/141472096/92dfc25e-70b2-44fc-bf2d-9038c3f2cb61)

![WhatsApp Image 2023-11-14 at 19 40 48_aafec728](https://github.com/Harish2404lll/softweb/assets/141472096/3fe9ab25-f7a3-4869-8d01-afc6202c84df)

![image](https://github.com/Harish2404lll/softweb/assets/141472096/b74ebd8a-7173-4801-8fe6-bbe505bc644a)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
