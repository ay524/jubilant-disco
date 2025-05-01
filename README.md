<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>BrightStart Solutions</title>
  <link rel="stylesheet" href="style.css">
  <style>
    :root {
      --primary: #0077cc;
      --secondary: #f4f4f4;
      --dark: #333;
      --light: #fff;
      --font-main:  sans-serif;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: var(--font-main);
      line-height: 1.6;
      background-color: var(--secondary);
      color: var(--dark);
    }

    header {
      background-color: var(--primary);
      color: var(--light);
      padding: 1rem 0;
      text-align: center;
    }

    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      gap: 2rem;
      background: var(--dark);
      padding: 1rem 0;
    }

    nav a {
      color: var(--light);
      text-decoration: none;
      font-weight: bold;
    }

    .container {
      width: 90%;
      margin: 2rem auto;
    }

    section {
      margin-bottom: 3rem;
      background: var(--light);
      padding: 2rem;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    section h2 {
      color: var(--primary);
      margin-bottom: 1rem;
    }

    footer {
      background: var(--dark);
      color: var(--light);
      text-align: center;
      padding: 1rem;
      position: relative;
      bottom: 0;
      width: 100%;
    }

    .team, .services, .testimonials, .contact {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
    }

    .card {
      flex: 1 1 30%;
      background: var(--secondary);
      padding: 1rem;
      border: 1px solid #ddd;
      border-radius: 5px;
    }

    form {
      display: flex;
      flex-direction: column;
    }

    input, textarea {
      padding: 0.5rem;
      margin-bottom: 1rem;
      border: 1px solid #ccc;
      border-radius: 3px;
    }

    button {
      padding: 0.7rem;
      background: var(--primary);
      color: var(--light);
      border: none;
      border-radius: 3px;
      cursor: pointer;
    }

    button:hover {
      background: #005fa3;
    }
  </style>
</head>
<body>
  <header>
    <h1>BrightStart Solutions</h1>
    <p>Your partner in digital innovation</p>
  </header>

  <nav>
    <ul>
      <li><a href="#about">About Us</a></li>
      <li><a href="#services">Services</a></li>
      <li><a href="#team">Team</a></li>
      <li><a href="#testimonials">Testimonials</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <div class="container">
    <section id="about">
      <h2>About Us</h2>
      <p>BrightStart Solutions is a forward-thinking digital agency helping small businesses achieve big results. From web design to marketing automation, our team brings creativity and technical expertise to every project.</p>
      <p>Founded in 2015, we’ve helped over 300 clients modernize their presence online. Our mission is simple: empower businesses to shine through effective digital strategies.</p>
    </section>

    <section id="services">
      <h2>Services</h2>
      <div class="services">
        <div class="card">
          <h3>Web Development</h3>
          <p>Responsive and SEO-friendly websites tailored to your brand.</p>
        </div>
        <div class="card">
          <h3>Branding</h3>
          <p>Custom logos, style guides, and brand messaging that connect with your audience.</p>
        </div>
        <div class="card">
          <h3>Digital Marketing</h3>
          <p>Comprehensive campaigns using Google Ads, social media, and email outreach.</p>
        </div>
        <div class="card">
          <h3>E-commerce</h3>
          <p>Launch and grow your online store with scalable solutions and easy integrations.</p>
        </div>
        <div class="card">
          <h3>Consulting</h3>
          <p>Expert insights to streamline operations and accelerate growth.</p>
        </div>
      </div>
    </section>

    <section id="team">
      <h2>Our Team</h2>
      <div class="team">
        <div class="card">
          <h3>abebe </h3>
          <p>Founder & CEO</p>
          <p>15+ years of experience in tech innovation and leadership.</p>
        </div>
        <div class="card">
          <h3>John Smith</h3>
          <p>Lead Developer</p>
          <p>Full-stack expert passionate about elegant, efficient code.</p>
        </div>
        <div class="card">
          <h3>Amara Lee</h3>
          <p>Marketing Director</p>
          <p>Creative thinker with a strong track record in digital strategy.</p>
        </div>
      </div>
    </section>

    <section id="testimonials">
      <h2>What Clients Say</h2>
      <div class="testimonials">
        <div class="card">
          <p>“BrightStart totally revamped our website. Their team is incredibly responsive and skilled.”</p>
          <p>- Sarah, Retail Business Owner</p>
        </div>
        <div class="card">
          <p>“Our e-commerce revenue tripled after working with BrightStart. Highly recommended!”</p>
          <p>- James, E-Commerce Entrepreneur</p>
        </div>
        <div class="card">
          <p>“They helped clarify our brand and launch a marketing campaign that brought in real results.”</p>
          <p>- Nina, Consultant</p>
        </div>
      </div>
    </section>

    <section id="contact">
      <h2>Contact Us</h2>
      <form>
        <input type="text" placeholder="Full Name" required>
        <input type="email" placeholder="Email Address" required>
        <textarea rows="4" placeholder="Your message..."></textarea>
        <button type="submit">Send Message</button>
      </form>
    </section>
  </div>

  <footer>
    <p>&copy; 2025 BrightStart Solutions. All rights reserved.</p>
  </footer>
</body>
</html>
