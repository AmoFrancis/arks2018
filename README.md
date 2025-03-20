<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>African Renaissance Komplex School</title>
    <link rel="stylesheet" href="assets/css/main.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header, nav, main, footer {
            text-align: center;
            padding: 20px;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav a {
            text-decoration: none;
            font-weight: bold;
        }
        form {
            max-width: 600px;
            margin: 0 auto;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 10px;
        }
        form input, form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        form button {
            padding: 10px 20px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        form button:hover {
            background-color: #45a049;
        }
        .map-container {
            text-align: center;
            margin: 20px 0;
        }
    </style>
</head>
<body>
    <header>
        <img src="images/logo.png" alt="ARKS Logo" width="150">
        <h1>African Renaissance Komplex School</h1>
        <p>Founded in Techiman, Bono East, in 2018. Inspiring young minds and shaping future leaders.</p>
    </header>
    
    <nav>
        <ul>
            <li><a href="#about">About Us</a></li>
            <li><a href="#programs">Programs</a></li>
            <li><a href="#admission">Admission</a></li>
            <li><a href="#calendar">Calendar</a></li>
            <li><a href="#service">Service</a></li>
            <li><a href="#computer-lab">Computer Lab</a></li>
            <li><a href="#library">Library</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    
    <main>
        <section id="about">
            <h2>About Us</h2>
            <p><strong>Vision:</strong> Transforming lives by instilling 21st-century skills.</p>
            <p><strong>Mission:</strong> Partnering with students, families, and the community.</p>
            <p><strong>Focus:</strong> STEAM: SCIENCE - TECHNOLOGY - ENGINEERING - ARTS - MATHEMATICS.</p>
            <p><strong>Values:</strong> RESPECTFUL - RESPONSIBLE - ROLE MODEL.</p>
            <p><strong>Motto:</strong> SILVER AND GOLD WILL PERISH, BUT GOOD EDUCATION WILL NEVER.</p>
        </section>
        
        <section id="computer-lab">
            <h2>Computer Laboratory</h2>
            <p>Our state-of-the-art computer lab provides students with hands-on experience in technology and computing.</p>
        </section>
        
        <section id="library">
            <h2>Library</h2>
            <p>Our well-stocked library offers a wide range of books and resources to enhance learning and research.</p>
            <img src="assets/images/library1.jpg" alt="Library Image 1" width="300">
            <img src="assets/images/library2.jpg" alt="Library Image 2" width="300">
        </section>
        
        <section id="contact">
            <h2>Contact Us</h2>
            <form action="https://formspree.io/f/{your_form_id}" method="POST">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="_replyto" placeholder="Your Email" required>
                <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
                <button type="submit">Send</button>
            </form>
            <div class="map-container">
                <h3>Our Location</h3>
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3153.019634507073!2d-122.419415484681!3d37.77492927975971!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8085809c5b0e6b1f%3A0x4c8b0b0b0b0b0b0b!2sAfrican%20Renaissance%20Komplex%20School!5e0!3m2!1sen!2sus!4v1633024800000!5m2!1sen!2sus" width="600" height="450" class="map-iframe" allowfullscreen="" title="School Location"></iframe>
            </div>
        </section>
    </main>
    
    <footer>
        <p><strong>Contact:</strong> 0531386248</p>
        <p><strong>Address:</strong> BT-0345-9729</p>
        <p>&copy; 2025 African Renaissance Komplex School. All rights reserved.</p>
        <ul>
            <li><a href="https://www.facebook.com/share/18EdtAzJPS/" target="_blank" rel="noopener">Facebook</a></li>
            <li><a href="https://www.instagram.com/arkseducation?igsh=cGMyMmFmOTJuNjZ4" target="_blank" rel="noopener">Instagram</a></li>
            <!-- Add more social media links if needed -->
        </ul>
    </footer>
</body>
</html>
