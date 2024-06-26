<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rafa's Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #1d1d1d;
            color: #ffffff;
        }
        .navbar {
            background-color: #333;
            padding: 10px;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        .navbar a {
            color: #ffffff;
            margin: 0 15px;
            text-decoration: none;
            transition: color 0.3s;
        }
        .navbar a:hover {
            color: #1e90ff;
        }
        .hero {
            background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcShqHIlA6RdbZGNIud9tLiKvnmNyExRTx6Zpw&s);
            background-size: cover;
            background-position: center;
            color: #ffffff;
            text-align: center;
            padding: 100px 20px;
            animation: fadeIn 2s ease-in-out;
        }
        .hero h1 {
            margin: 0;
            font-size: 50px;
        }
        .content {
            padding: 40px 20px;
            text-align: center;
        }
        .footer {
            background-color: #fdfafa;
            color: #04ff58;
            text-align: center;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }
        @keyframes slideIn {
            from {
                transform: translateY(50px);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }
        .content h2 {
            animation: slideIn 1s ease-in-out;
        }
        .services, .contact {
            margin-top: 40px;
        }
        .services .service-item, .contact .contact-item {
            margin: 20px 0;
            animation: slideIn 1s ease-in-out;
        }
    </style>
</head>
<body>

    <div class="navbar">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </div>

    <div class="hero" id="home">
        <h1>Welcome to Rafa's Portfolio</h1>
        <p>Discover my work and skills</p>
    </div>

    <div class="content" id="about">
        <h2>About Me</h2>
        <p>Hi, I'm Rafa, a passionate developer with expertise in web development and design. I love creating beautiful, functional websites that help businesses succeed online.</p>
    </div>

    <div class="content services" id="services">
        <h2>My Services</h2>
        <div class="service-item">
            <h3>Web Development</h3>
            <p>Building responsive and interactive websites.</p>
        </div>
        <div class="service-item">
            <h3>UI/UX Design</h3>
            <p>Creating user-friendly interfaces and experiences.</p>
        </div>
        <div class="service-item">
            <h3>SEO Optimization</h3>
            <p>Improving your website's visibility on search engines.</p>
        </div>
    </div>

    <div class="content contact" id="contact">
        <h2>Contact Me</h2>
        <div class="contact-item">
            <p>Email: rafa@example.com</p>
        </div>
        <div class="contact-item">
            <p>FB: <a href="https://www.facebook.com/S.F.RAFA.2008" style="color: #1e90ff;">https://www.facebook.com/S.F.RAFA.2008</a></p>
        </div>
        <div class="contact-item">
            <p>Phone: 01961263433</p>
        </div>
    </div>

    <div class="footer">
        <p>&copy; 2024 Rafa's Portfolio</p>
    </div>

</body>
</html>
