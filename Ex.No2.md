# Ex02 Commercial Website
## Date:

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
## HOME
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HOME PAGE</title>
</head>
<style type="text/css">
	.form {
		margin: 0 auto;
		width: 210px;
	}

	.form label{
		display: inline-block;
		text-align: right;
		float: left;
	}

	.form input{
		display: inline-block;
		text-align: left;
		float: right;
	}
</style>
<body style="background-image: url(home.jpg);background-size: cover;">
    <marquee behavior="" direction="right" style="color: burlywood;">WELCOME TO OUR SITE</marquee>
    <h1 style="text-align: center;color: wheat; padding: 50px;margin: auto; font-style:italic; font-weight: 100px;">TECHZ SHOP</h1>
    <h2 style="text-align: center;color: white;">LOGIN / SIGN UP</h2>
    <br>
    <br>
    <form>
    <div class="form">
		<label style="color: aqua;">E-MAIL</label>
        <br>
		<input type="text" placeholder="Enter email">
        <br>
        <br>
		<label style="color: aqua;">PASSWORD</label>
		<input type="password" placeholder="" required>
        <br>
        <br>
		<nav>
			<a href="http://127.0.0.1:5500/sam.html" style="text-decoration: none; color:white;display: block;margin: 55px;"t target="_blank">LOGIN</a>
		</nav>
	</div>
    </form>
</body>
</html>

```
## CODE 1
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PRODUCTS</title>
    <style>
        .container{
            margin: 20px;
            padding: 20px;
            border: 10px;
            display: flex;
            justify-content: center;
            flex-direction: row;
            flex-wrap: wrap;
            border: 10px solid black;}
        .box{
            margin: 10px;
            padding: 20px;
            font-size: larger;
            font-style: italic;
            border: 3px solid black;
        }

    </style>
</head>
<body>
    <h1 style="text-align: center;">SAMSUNG</h1>
    <header style="color: bisque;">
            <nav  style=" text-align:end;">
                <a href="http://127.0.0.1:5500/apple.html" style="text-decoration: none; color: black; text-align: center; padding: 20px;">APPLE STORE</a>
                <a href="http://127.0.0.1:5500/oneplus.html" style="text-decoration: none; color: black; text-align: center; padding: 08px;">ONEPLUS STORE</a>
            </nav>
    </header>
    <div class="container">
        <div class="box"><img src="sph.jpg" alt="" height="200px" width="200px" ></div>
        <div class="box"><img src="shd.jpg" alt="" height="200px" width="200px" ></div>
        <div class="box"><img src="sar.jpg" alt="" height="200px" width="200px" ></div>
        <div class="box"><img src="swt.jpg" alt="" height="200px" width="200px" ></div>
    </div>
    <H3 style="text-align: center;color:black;font-style: italic;">FOR ORDERS CALL : 6587965412 ** E-mail:techzshop@gmail.com</H3>
</body>
</html>
```
## CODE 2
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PRODUCTS</title>
    <style>
        .container{
            margin: 20px;
            padding: 20px;
            border: 10px;
            display: flex;
            justify-content: center;
            flex-direction: row;
            flex-wrap: wrap;
            border: 10px solid black;}
        .box{
            margin: 10px;
            padding: 20px;
            font-size: larger;
            font-style: italic;
            border: 3px solid black;
        }

    </style>
</head>
<body>
    <h1 style="text-align: center;">SAMSUNG</h1>
    <header style="color: bisque;">
            <nav  style=" text-align:end;">
                <a href="http://127.0.0.1:5500/apple.html" style="text-decoration: none; color: black; text-align: center; padding: 20px;">APPLE STORE</a>
                <a href="http://127.0.0.1:5500/oneplus.html" style="text-decoration: none; color: black; text-align: center; padding: 08px;">ONEPLUS STORE</a>
            </nav>
    </header>
    <div class="container">
        <div class="box"><img src="sph.jpg" alt="" height="200px" width="200px" ></div>
        <div class="box"><img src="shd.jpg" alt="" height="200px" width="200px" ></div>
        <div class="box"><img src="sar.jpg" alt="" height="200px" width="200px" ></div>
        <div class="box"><img src="swt.jpg" alt="" height="200px" width="200px" ></div>
    </div>
    <H3 style="text-align: center;color:black;font-style: italic;">FOR ORDERS CALL : 6587965412 ** E-mail:techzshop@gmail.com</H3>
</body>
</html>
```
## CODE 3
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>cookies</title>
    <style>
        .container{
            margin: 5px;
            padding: 20px;
            border: 8px;
            display: flex;
            justify-content: center;
            flex-direction: row;
            flex-wrap: wrap;
            border: 10px solid black;}
        .box{
            margin: 10px;
            padding: 20px;
            font-size: larger;
            font-style: italic;
            border: 3px solid black;
        }

    </style>
</head>
<body>
    <h1 style="text-align: center;">APPLE</h1>
    <header style="color: bisque;">
            <nav  style=" text-align:end;">
                <a href="http://127.0.0.1:5500/sam.html" style="text-decoration: none; color: black; text-align: center; padding: 20px;">SAMSUNG </a>
                <a href="http://127.0.0.1:5500/apple.html" style="text-decoration: none; color: black; text-align: center; padding: 20px;">APPLE</a>
                <a href="http://127.0.0.1:5500/oneplus.html" style="text-decoration: none; color: black; text-align: center; padding: 08px;">ONEPLUS</a>
            </nav>
    </header>
    <div class="container">
        <div class="box"><img src="aph.jpg" alt="" height="200px" width="200px" ></div>
        <div class="box"><img src="atb.jpg" alt="" height="200px" width="200px" ></div>
        <div class="box"><img src="ahd.jpg" alt="" height="200px" width="200px" ></div>
        <div class="box"><img src="aar.jpg" alt="" height="200px" width="200px" ></div>
    </div>
    <footer>
        <H3 style="text-align: center;color:black;font-style: italic;">FOR ORDERS CALL : 6587965412 ** E-mail:techzshop@gmail.com</H3>
    </footer>
    
</body>
</html>
```
## CODE 4
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>fruits</title>
    <style>
        .container{
            margin: 20px;
            padding: 20px;
            border: 10px;
            display: flex;
            justify-content: center;
            flex-direction: row;
            flex-wrap: wrap;
            border: 10px solid black;}
        .box{
            margin: 10px;
            padding: 20px;
            font-size: larger;
            font-style: italic;
            border: 3px solid black;
        }

    </style>
</head>
<body>
    <h1 style="text-align: center;">ONEPLUS</h1>
    <header style="color: bisque;">
            <nav  style=" text-align:end;">
                <a href="http://127.0.0.1:5500/sam.html" style="text-decoration: none; color: black; text-align: center; padding: 20px;">SAMSUNG </a>
                <a href="http://127.0.0.1:5500/apple.html" style="text-decoration: none; color: black; text-align: center; padding: 20px;">APPLE </a>
                <a href="http://127.0.0.1:5500/oneplus.html" style="text-decoration: none; color: black; text-align: center; padding: 08px;">ONEPLUS</a>
            </nav>
    </header>
    <div class="container">
        <div class="box"><img src="opd.jpg" alt="" height="200px" width="200px" ></div>
        <div class="box"><img src="oph.jpg" alt="" height="200px" width="200px" ></div>
        <div class="box"><img src="owt.jpg" alt="" height="200px" width="200px" ></div>
        <div class="box"><img src="oar.jpg" alt="" height="200px" width="200px" ></div>
    </div>
    <H3 style="text-align: center;color:black;font-style: italic;">FOR ORDERS CALL : 6587965412 ** E-mail:techzshop@gmail.com</H3>
</body>
</html>

```
## OUTPUT

![Screenshot 2025-05-04 102337](https://github.com/user-attachments/assets/b149c058-902d-42fc-8b41-b39402f35068)
![Screenshot 2025-05-04 102351](https://github.com/user-attachments/assets/7f1a7fa3-f8c8-48e8-ab2a-0c24ee000f28)
![Screenshot 2025-05-04 102410](https://github.com/user-attachments/assets/f0f63eb4-eb70-42f3-87f7-decba1048dc6)
![Screenshot 2025-05-04 102326](https://github.com/user-attachments/assets/d48dce02-5d83-4e24-bad5-23b0a71e8046)


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.![Screenshot 2025-05-04 102337](https://github.com/user-attachments/assets/99d904ee-d4e8-4824-b30d-df88e407ff00)
