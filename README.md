# Oascent-site
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Oascent Automation - AI-Powered Brand Solutions</title>
    <style>
        :root {
            --primary: #2A5CAA;
            --secondary: #FF6B35;
            --light: #F7F9FC;
            --dark: #1A1A2E;
        }
        body {
            font-family: 'Segoe UI', sans-serif;
            margin: 0;
            padding: 0;
            color: var(--dark);
            line-height: 1.6;
        }
        header {
            background: var(--primary);
            color: white;
            padding: 1rem;
            text-align: center;
        }
        .logo {
            font-size: 1.8rem;
            font-weight: bold;
            margin-bottom: 0.5rem;
        }
        .tagline {
            font-size: 1rem;
            opacity: 0.9;
        }
        nav {
            display: flex;
            justify-content: space-around;
            background: var(--dark);
            padding: 0.8rem 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-size: 0.9rem;
        }
        .hero {
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('ai-background.jpg');
            background-size: cover;
            color: white;
            padding: 3rem 1rem;
            text-align: center;
        }
        .cta-button {
            background: var(--secondary);
            color: white;
            padding: 0.8rem 1.5rem;
            border: none;
            border-radius: 5px;
            font-weight: bold;
            margin-top: 1rem;
            display: inline-block;
        }
        section {
            padding: 2rem 1rem;
        }
        h2 {
            color: var(--primary);
            text-align: center;
        }
        .service-card {
            background: var(--light);
            border-radius: 8px;
            padding: 1.5rem;
            margin: 1rem 0;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        footer {
            background: var(--dark);
            color: white;
            text-align: center;
            padding: 1.5rem;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">OASCENT AUTOMATION</div>
        <div class="tagline">AI-Powered Brand Solutions</div>
    </header>
    
    <nav>
        <a href="#services">Services</a>
        <a href="#about">About</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact</a>
    </nav>
    
    <section class="hero">
        <h1>Transform Your Brand with AI Automation</h1>
        <p>We build powerful brands, automate social content, and create stunning websites - all powered by cutting-edge AI technology.</p>
        <a href="#contact" class="cta-button">Get Started Today</a>
    </section>
    
    <section id="services">
        <h2>Our Services</h2>
        <div class="service-card">
            <h3>AI Brand Building</h3>
            <p>From logo design to complete brand identity systems, our AI tools help create distinctive brands that stand out.</p>
        </div>
        <div class="service-card">
            <h3>Social Media Automation</h3>
            <p>Automated content creation, scheduling, and analytics to keep your social presence vibrant 24/7.</p>
        </div>
        <div class="service-card">
            <h3>AI Website Development</h3>
            <p>Smart websites that adapt to your visitors, with automated content updates and SEO optimization.</p>
        </div>
    </section>
    
    <section id="about">
        <h2>About Oascent Automation</h2>
        <p>We combine human creativity with artificial intelligence to deliver branding and digital solutions at scale. Our proprietary automation tools allow us to deliver high-quality results faster and more efficiently than traditional agencies.</p>
    </section>
    
    <section id="contact">
        <h2>Ready to Automate Your Success?</h2>
        <p>Contact us today for a free consultation and demo of our AI-powered solutions.</p>
        <form>
            <input type="text" placeholder="Your Name" style="width:100%; padding:0.8rem; margin:0.5rem 0; border:1px solid #ccc; border-radius:5px;">
            <input type="email" placeholder="Email Address" style="width:100%; padding:0.8rem; margin:0.5rem 0; border:1px solid #ccc; border-radius:5px;">
            <textarea placeholder="How can we help?" style="width:100%; padding:0.8rem; margin:0.5rem 0; border:1px solid #ccc; border-radius:5px; height:100px;"></textarea>
            <button type="submit" class="cta-button" style="width:100%;">Send Message</button>
        </form>
    </section>
    
    <footer>
        <p>&copy; 2023 Oascent Automation. All rights reserved.</p>
        <p>AI-Powered Brand Solutions</p>
    </footer>
</body>
</html>