
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Simple Website</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
        }
        
        header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 1.5rem 0;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        header h1 {
            text-align: center;
            font-size: 2rem;
            margin-bottom: 1rem;
        }
        
        nav {
            text-align: center;
        }
        
        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 2rem;
            flex-wrap: wrap;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            padding: 0.5rem 1rem;
            border-radius: 5px;
            transition: background 0.3s;
        }
        
        nav a:hover {
            background: rgba(255, 255, 255, 0.2);
        }
        
        main {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 2rem;
        }
        
        section {
            margin-bottom: 3rem;
        }
        
        article {
            background: white;
            padding: 2rem;
            margin-bottom: 2rem;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        
        h2 {
            color: #667eea;
            margin-bottom: 1rem;
            font-size: 1.8rem;
        }
        
        h3 {
            color: #764ba2;
            margin: 1.5rem 0 0.5rem;
            font-size: 1.3rem;
        }
        
        p {
            margin-bottom: 1rem;
            text-align: justify;
        }
        
        aside {
            background: #f8f9fa;
            padding: 1.5rem;
            border-left: 4px solid #667eea;
            margin: 1.5rem 0;
            border-radius: 4px;
        }
        
        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 2rem;
            margin-top: 3rem;
        }
        
        footer h3 {
            color: white;
            margin-bottom: 1rem;
        }
        
        footer p {
            margin-bottom: 0.5rem;
        }
        
        footer a {
            color: #667eea;
            text-decoration: none;
        }
        
        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home">
            <article>
                <h2>Introduction to Our Site</h2>
                <p>Welcome to our website! We're excited to have you here.</p>
                
                <h3>What We Offer</h3>
                <p>Our platform provides a variety of services tailored to meet your needs. Whether you're looking for information, resources, or simply browsing, we've got you covered with quality content and user-friendly navigation.</p>
                
                <aside>
                    <h3>Did You Know?</h3>
                    <p>Semantic HTML helps search engines better understand your content.</p>
                </aside>
            </article>

            <article>
                <h2>Featured Content</h2>
                <p>Check out our latest updates and featured article.</p>
                
                <h3>Why Choose Us?</h3>
                <ul>
                    <li>Professional and reliable service</li>
                    <li>User-friendly interface</li>
                    <li>Regular updates and fresh content</li>
                   
                </ul>
                
                <h3>Get Started Today</h3>
                <p>Ready to explore more? Navigate through our site using the menu above, or scroll down to find our contact information. We're here to help you every step of the way!</p>
            </article>
        </section>
    </main>

    <footer>
        <h3>Contact Information</h3>
        <p>Email: <a href="mailto:info@example.com">info@example.com</a></p>
        <p>Phone: <a href="tel:+1234567890">09776578171</a></p>
        <p>&copy; 2024 My Website. All rights reserved.</p>
    </footer>
</body>
</html>
