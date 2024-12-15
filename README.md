<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DialogSphere AI</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            padding: 20px;
        }
        .services, .about, .contact, .dashboard {
            margin: 20px 0;
        }
        .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
        .btn {
            display: inline-block;
            padding: 10px 15px;
            background-color: #4CAF50;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
        .btn:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

<header>
    <h1>DialogSphere AI</h1>
    <p>Transforming Conversations, Revolutionizing Business</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#services">Services</a>
    <a href="#about">About Us</a>
    <a href="#contact">Contact</a>
    <a href="#dashboard">Dashboard</a>
</nav>

<div class="container" id="home">
    <h2>Welcome to DialogSphere AI</h2>
    <p>Empowering businesses through custom conversational AI solutions. Enhance customer engagement, streamline operations, and improve user experiences.</p>
    <a href="#contact" class="btn">Get Started</a>
</div>

<div class="container services" id="services">
    <h2>Our Services</h2>
    <ul>
        <li><strong>Chatbot Development:</strong> Custom bots for customer support, e-commerce, and healthcare.</li>
        <li><strong>Voice Assistant Integration:</strong> Streamline interactions with intelligent voice support.</li>
        <li><strong>AI-Powered IVR Systems:</strong> Enhance customer interactions through AI-driven IVRs.</li>
        <li><strong>Conversational Design:</strong> Optimize dialogue flows for improved customer engagement.</li>
        <li><strong>Analytics and Performance Tracking:</strong> Detailed reports and insights to refine AI solutions.</li>
        <li><strong>Multilingual AI Support:</strong> Solutions that break language barriers globally.</li>
    </ul>
</div>

<div class="container about" id="about">
    <h2>About Us</h2>
    <p>At DialogSphere AI, we aim to revolutionize the conversational AI industry by delivering tailored solutions that meet your business needs. Our team is comprised of industry experts passionate about empowering businesses through technology.</p>
</div>

<div class="container contact" id="contact">
    <h2>Contact Us</h2>
    <p>Have questions? Ready to transform your business? Reach out to us!</p>
    <form action="#">
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name" required><br>

        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br>

        <label for="message">Message:</label><br>
        <textarea id="message" name="message" rows="5" required></textarea><br>

        <button type="submit" class="btn">Submit</button>
    </form>
</div>

<div class="container dashboard" id="dashboard">
    <h2>Client Dashboard</h2>
    <p>Log in to manage your projects, access analytics, and monitor progress.</p>
    <a href="#" class="btn">Log In</a>
</div>

<footer class="footer">
    <p>&copy; 2024 DialogSphere AI. All rights reserved.</p>
</footer>

</body>
</html>
