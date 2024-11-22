<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Travel in Stellies</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap'); 
        body {
            font-family: 'Montserrat', sans-serif; 
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #ff6347 3px solid; 
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            float: left;
            display: inline;
            padding: 0 20px 0 20px;
        }
        .showcase {
            min-height: 400px;
            background: url('showcase.jpg') no-repeat center center/cover; 
            text-align: center;
            color: #ed2828;
        }
        .showcase h1 {
            margin-top: 100px;
            font-size: 55px;
            margin-bottom: 10px;
        }
        .showcase p {
            font-size: 20px;
        }
        .button {
            display: inline-block;
            color: #fff;
            background: #ff6347;
            padding: 10px 20px;
            text-decoration: none;
            font-size: 18px;
            border-radius: 5px;
        }
        .image-container {
            text-align: center;
            margin: -50px 0 20px 0; 
        }
        .image-container img {
            max-width: 70%;
            height: auto;
            border-radius: 10px; 
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1><span class="highlight">Blog to get great deals in Stellies:</span> Making life easier for you</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="home.html">Home</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="services.html">Services</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="showcase">
        <div class="container">
            <h1>I LOVE STELLIES</h1>
            <p>"Affordable activities, with a great view"</p>
            <a href="about.html" class="button">Learn More</a>
        </div>
    </section>

    <section class="image-container">
        <img src="Stellies.jpg" alt="Description of the image">
    </section>
</body>
</html>




