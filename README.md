<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Awesome Landing Page</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
        }

        body {
            line-height: 1.5;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        .header {
            background-color: #182230;
            color: white;
            padding: 2px  128px;
        }
        .logo{
            width: 250x;
            height: 200px;
            
        }
        .nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 0;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
            color: #f9faf8;
            position: relative;
        }

        .nav-links {
            display: flex;
            gap: 24px;
        }

        .nav-links a {
            color: #e5e7eb;
            text-decoration: none;
            font-size: 18px;
        }

        .hero {
            display: flex;
            justify-content: space-between;
            align-items: center;
            gap: 48px;
            padding: 64px 0;
        }

        .hero-content {
            flex: 1;
        }

        .hero h1 {
            font-size: 48px;
            font-weight: 900;
            color: #f9faf8;
            line-height: 1.1;
            margin-bottom: 12px;
        }

        .hero p {
            font-size: 18px;
            color: #e5e7eb;
            margin-bottom: 16px;
            max-width: 460px;
        }

        .hero-image {
            flex: 1;
            background-color: #4c515a;
            height: 240px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #fff;
            text-align: center;
            overflow: hidden;
        }

        .button {
            background-color: #1f71f5;
            color: white;
            padding: 8px 32px;
            border-radius: 8px;
            text-decoration: none;
            font-weight: bold;
            display: inline-block;
            font-size: 18px;
            border: none;
        }

        .features {
            padding: 80px 0;
            text-align: center;
        }

        .features h2 {
            font-size: 36px;
            font-weight: 900;
            color: #1f2937;
            margin-bottom: 48px;
        }

        .feature-grid {
            display: flex;
            justify-content: center;
            gap: 52px;
            margin: 0 auto;
            max-width: 1000px;
        }
        .bongo {
            width: 192px;
            height: 170px;
            transition: transform 0.3s ease, opacity 0.3s ease;
        }
        .bingo {
             
            width: 192px;
            height: 172px;
           
        }
        .born {
             
            width: 192px;
            height: 170px;
         
        }
        .stay {
             
            width: 192px;
            height: 172px;
          
        }

        .feature-item {
            flex: 1;
            max-width: 200px;
        }

        .feature-box {
            border: 4px solid #0c63f0;
            border-radius: 16px;
            height: 160px;
            margin-bottom: 16px;
            overflow: hidden;
        }

        .feature-item p {
            font-size: 18px;
            color: #4b5563;
        }

        .testimonial {
            background-color: #a7a8aa;
            padding: 120px 0;
        }

        .testimonial-content {
            max-width: 800px;
            margin: 0 auto;
            padding: 0 20px;
        }

        .quote {
            font-family: Georgia, 'Times New Roman', Times, serif;
            font-size: 36px;
            color: #1f2937;
            font-weight: 300;
            margin-bottom: 16px;
        }

        .author {
            text-align: right;
            font-weight: bold;
            font-size: 24px;
            color: #1f2937;
        }

        .cta-section {
            padding: 80px 0;
        }

        .cta-container {
            background-color: #0857d6;
            border-radius: 8px;
            color: white;
            padding: 48px 96px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .cta-text h3 {
            font-size: 24px;
            margin-bottom: 4px;
        }

        .cta-text p {
            color: #e5e7eb;
        }
        .pexels {
            width: 600px;
            height: 400px;
        }

        .cta-button {
            border: 2px solid white;
        }

        .footer {
            background-color: #1f2937;
            color: #e5e7eb;
            text-align: center;
            padding: 40px 0;
        }
    </style>
</head>
<body>
    <div class="header">
        <div class="container">
            <nav class="nav">
                <div class="logo"><img src="BEN THE BEATS.png" alt="Bernard" class="logo"></div>
                <div class="nav-links">
                    <a href="firstname.html">First Name</a>
                    <a href="secondname.html">Second name</a>
                    <a href="id.html">Id Number</a>
                </div>
            </nav>
            <div class="hero">
                <div class="hero-content">
                    <h1>The Reality Of The Nature</h1>
                    <p> The relity of the nature is a topic that has puzzled philosophers for centuries.</p>
                    <a href="#" class="button">Sign up</a>
                </div>
                <div class="hero-image">
                    <img src="pexels-eberhardgross-443446.jpg" alt="Wallpaper" class="pexels">
                </div>
            </div>
        </div>
    </div>
    <div class="features">
        <div class="container">
            <h2 style="font-family: Georgia, 'Times New Roman', Times, serif;">Some random information.</h2>
            <div class="feature-grid">
                <div class="feature-item">
                    <div class="feature-box"><img src="born.jpg" alt="born" class="born"></div>
                    <p style="font-family: Georgia, 'Times New Roman', Times, serif;">What is The Nature of Reality? It’s a blog, and it’s pretty much the biggest question.</p>
                </div>
                <div class="feature-item">
                    <div class="feature-box"><img src="bongo.jpg" alt="bongo" class="bongo"></div>
                    <p style="font-family: Georgia, 'Times New Roman', Times, serif;">Reality can be defined in a way that links it to worldviews or parts of them conceptual frameworks</p>
                </div>
                <div class="feature-item">
                    <div class="feature-box"><img src="bingo.jpg" alt="bingo" class="bingo"></div>
                    <p style="font-family: Georgia, 'Times New Roman', Times, serif;">Reality is the totality of all things, structures, events , and phenomena.</p>
                </div>
                <div class="feature-item">
                    <div class="feature-box"><img src="staypositive.jpg" alt="staypositive" class="stay"></div>
                    <p style="font-family: Georgia, 'Times New Roman', Times, serif;">Out of all the realities, the reality of everyday life is the most important one since, our consciousness</p>
                </div>
            </div>
        </div>
    </div>

    <div class="testimonial">
        <div class="testimonial-content">
            <div class="quote">Reality is the sum or aggregate of all that is real or existent within the universe, as opposed to that which is only imaginary, nonexistent or nonactual. The term is also used to refer to the ontological status of things, indicating their existence.</div>
            <div class="author"><b>Reality Of The Nature</b>></div>
        </div>
    </div>

    <div class="cta-section">
        <div class="container">
            <div class="cta-container">
                <div class="cta-text">
                    <h3>Call to action! It's time!</h3>
                    <p>Sign up for our product by clicking that button right over there!</p>
                </div>
                <a href="#" class="button cta-button">Sign up</a>
            </div>
        </div>
    </div>

    <footer class="footer">
        <div class="container">
             @to Bernard 2024
        </div>
    </footer>
</body>
</html>
