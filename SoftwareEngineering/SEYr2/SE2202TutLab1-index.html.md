```html
<html>

<head>
    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
        }

  

        .topnav {
            overflow: hidden;
            background-color: #333;
        }
  
        .topnav a {
            float: left;
            color: #f2f2f2;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
            font-size: 17px;
        }

        .topnav a:hover {
            background-color: #ddd;
            color: black;
        }

  

        .topnav a.active {
            background-color: darkcyan;
            color: white;
        }

  

        .hero-image {
            background-image: linear-gradient(rgba(0, 0, 0, .5), rgba(0, 
             0, 0, .5)), url("Capture32.png");
            height: 50%;
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
            position: relative;
        }

  

        .hero-text {
            text-align: center;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            color: white;
        }

        .about-section {
            background-image: url("Capture47V2.png");
            padding: 190px;
            text-align: center;
            background-color: #474e5d;
            color: white;
        }

        .about-me {
            background-color: darkcyan;
            color: #f2f2f2;
            margin: 10px;
            padding: 10px;
        }
  
        .about-text {
            margin: 10px;
        }

  

        .title {
            color: darkslategray;
            font-size: xx-large;
        }

  

        .contact {
            background-color: darkcyan;
            margin: 10px;
            padding: 10px;
        }

  

        .contact-text {
            text-align: center;
            margin: 10px;
            color: white;
        }
    </style>
</head>

  

<title>Jacob Dreyer</title>

<div class="topnav">
    <a class="active" href="#home">Home</a>
    <a href="#contact">Contact</a>
    <a href="#about">About</a>
</div>

<div class="hero-image">
    <div class="hero-text">
        <h1>
            Jacob Dreyer
        </h1>
        <p>I'm a Software Engineering Student at Western University</p>
        <a href="#contact">Contact Me</a>
    </div>
</div>

<div class="about-section">
    <h1 id="about">About Me</h1>
</div>

<div class="about-me">
    <div class="about-text">
    <h3 class="title">Student</h3>
    <h2>Education</h2>
    <p>I am currently in my second year of software engineering at 
     Western University</p>
    <p>I am currently learning how to code with java, JavaScript, HTML, 
     and CSS </p>
    <h2>Hobbies</h2>
    <p>In my free time I enjoy playing video games and watching 
     formula1. I also enjoy the outdoors and doing things like camping, 
     skiing, and playing hockey</p>
    </div>
</div>

  

<div class="contact">
    <div class="contact-text">
        <h2 id="contact" class="title">My Contact Information</h2>
        <p>Email: jdreyer4@uwo.ca</p>
    </div>
</div>

</html>
```