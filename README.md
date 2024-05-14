# Project Responsive Web Design using Bootstrap
## Date:

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>CodeCraft</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'Courier New', Courier, monospace;
                        }
            .banner {
                width: 100%;
                height: 100vh;
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 100%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color:gold;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: white;
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color:black;
                border-radius: 10px;
                background:gold;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color:gold;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .container {
                background: transparent;
                padding: 10px 5%;
                padding-bottom: 100px;
            }
            .container .box-container {
                display: grid;
                grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
                gap: 20px;
            }
            .container .box-container .box {
                color: white;
                box-shadow: 0 5px 10px rgba(0,0,0,.2);
                border-radius: 10px;
                background: transparent;
                border: 1px solid white;
                padding: 10px 5px;
            }
            .container .box-container .box img {
                height: 50px;
                border-radius: 20px;
            }
            .container .box-container .box h3 {
                color: gold;
                font-size: large;
                padding: 10px 0;
            }
            .container .box-container .box p {
                color: white;
                font-size: small;
                line-height: 1.5;
            }
            footer {
                background-color: gold;
                margin-top: auto;
            }
        </style>
    </head>
<body background="imge.jpeg">
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">C<span>ode</span>V<span>erse</span></h1>
            <ul>
                <li><a href="home.html"> Home </a></li>
                <li><a href="products.html"> Products </a></li>
                <li><a href="person.html"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="container">
            <div class="box-container">
                <div class="box">
                    <img src="py logo.jpeg" alt="">
                    <h3>Python</h3>
                    <p>Where simplicity meets power in the world of programming.</p>
                </div>
                <div class="box">
                    <img src="c logo.jpeg" alt="">
                    <h3>C pgg </h3>
                    <p> Coding resilience in C: Unleashing the raw power of systems programming.</p>
                </div>
                <div class="box">
                    <img src="c++.png" alt="">
                    <h3>C++ pgg</h3>
                    <p>Elevating possibilities with the perfect blend of efficiency and object-oriented elegance.</p>
                </div>
                <div class="box">
                    <img src="java.png" alt="">
                    <h3>Java</h3>
                    <p>Brewing cross-platform magic with the steaming cup of robust and versatile programming.</p>
                </div>
                <div class="box">
                    <img src="java s.png" alt="">
                    <h3>Java Script</h3>
                    <p>Transforming web landscapes with dynamic interactivity and client-side wizardry.</p>
                </div>
                <div class="box">
                    <img src="sql.png" alt="">
                    <h3>SQL</h3>
                    <p>It is used to manage data in database management system and particularly useful in handling structured data.</p>
                </div>
                <div class="box">
                    <img src="html.png" alt="">
                    <h3>HTML</h3>
                    <p>designed to be displayed in a web browser. It defines the content and structure of web content. </p>
                </div>
                <div class="box">
                    <img src="css.png" alt="">
                    <h3>CSS</h3>
                    <p>CSS basics walks through what you need to get started.a simple mechanism for adding style</p>
                </div>
                <div class="box">
                    <img src="c1.png" alt="">
                    <h3>C#</h3>
                    <p> a general-purpose high-level programming language supporting multiple paradigms</p>
                </div>
                <div class="box">
                    <img src="php.png" alt="">
                    <h3>PHP</h3>
                    <p>a server scripting language, and a powerful tool for making dynamic and interactive Web pages. </p>
                </div>
                <div class="box">
                    <img src="go.png" alt="">
                    <h3>GO</h3>
                    <p>open source programming language that makes it simple to build secure, scalable systems.</p>
                </div>
                <div class="box">
                    <img src="ruby.png" alt="">
                    <h3>RUBY</h3>
                    <p> open source programming language with a focus on simplicity and productivity..</p>
                </div>
 
            </div>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by Shyam Kumar E (2122230207) </center>
    </footer>
</body>
</html>
```


## OUTPUT:
![Screenshot 2024-05-14 204012](https://github.com/Romanshyam/Pharma/assets/123962992/280df20b-6652-4a83-8285-a24191cdf0a8)



## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
