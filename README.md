# CSS Layouts and Responsive Design

## Objectives

Implement Flexbox and Grid for layout design.
Make the webpage responsive using media queries.
Ensure proper alignment and spacing.

## Instructions

- use Flexbox or CSS Grid.
- Add a navigation bar and structure the content.
- Use media queries to adjust layout for mobile, tablet, and desktop.

>[!NOTE]
>  - Include at least:
>  - navigation bar
>  - media queries

# Tasks

- Apply Flexbox or Grid for layout.
- Make the page responsive.
- Test across different screen sizes.

Happy Coding! 💻✨


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Evansco Limited</title>
  <style>
    html {
      scroll-behavior: smooth;
    }

    body {
      margin: 0;
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background-color: skyblue; /* Set background color to sky blue */
    }

    header {
      background: rgba(51, 51, 51, 0.9);
      color: #fff;
      padding: 1rem 2rem;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      margin-left: 1rem;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .container {
      padding: 2rem;
    }

    section {
      margin-bottom: 2rem;
    }

    footer {
      background: rgba(51, 51, 51, 0.9);
      color: #fff;
      text-align: center;
      padding: 1rem;
    }
  </style>
</head>
<body>
  <header>
    <nav>
      <div class="logo">Evansco</div>
      <div class="nav-links">
        <a href="#home">Home</a>
        <a href="#services">Services</a>
        <a href="#about">About</a>
        <a href="#clients">Clients</a>
        <a href="#contact">Contact</a>
        <a href="#follow-us">Follow Us</a>
        <a href="#chat-with-us">Chat</a>
      </div>
    </nav>
  </header>

  <main class="container">
    <section id="home">
      <h2>Welcome to Evansco Limited</h2>
      <p>We provide a full range of accounting services tailored to meet the unique needs of each client.</p>
    </section>

    <section id="services">
      <h3>Our Services</h3>
      <ul>
        <li>Bookkeeping and Accounting</li>
        <li>Tax Preparation and Planning</li>
        <li>Auditing Services</li>
        <li>Financial Statement Preparation</li>
        <li>Management Accounting</li>
        <li>Budgeting and Forecasting</li>
        <li>Internal Controls Review</li>
        <li>Business Advisory</li>
        <li>Financial Consulting</li>
        <li>Forensic Accounting</li>
        <li>VAT and Other Statutory Compliance</li>
      </ul>
    </section>

    <section id="about">
      <h3>About Us</h3>
      <p>Evansco is committed to delivering top-tier financial and accounting services with integrity and professionalism.</p>
      <p>Our team of experts is dedicated to helping businesses navigate the complexities of financial management.</p>
      <p>We pride ourselves on our personalized approach, ensuring that each client receives the attention and service they deserve.</p>
    </section>

    <section id="clients">
      <h3>Our Clients</h3>
      <p>We proudly serve a wide range of clients across various industries. Some of our esteemed clients include:</p>
      <ul>
        <li>ABC Manufacturing Ltd.</li>
        <li>BlueSky Technologies</li>
        <li>HealthPlus Clinics</li>
        <li>Greentech Innovations</li>
        <li>UrbanStyle Enterprises</li>
        <li>SmartFarm Solutions</li>
      </ul>
    </section>

    <section id="contact">
      <h3>Contact Us</h3>
      <p>Email: info@evansco.com<br>Phone: +254 700 000000<br>Location: Nairobi, Kenya</p>
    </section>

    <section id="follow-us">
      <h3>Follow Us</h3>
      <p>Stay connected with us on social media:</p>
      <ul>
        <li>
          <a href="https://www.facebook.com/evanscoltd" target="_blank">
            <img src="assets/facebook-icon.png" alt="Facebook" width="24" height="24">
          </a>
        </li>
        <li>
          <a href="https://www.twitter.com/evanscoltd" target="_blank">
            <img src="assets/twitter-icon.png" alt="X" width="24" height="24">
          </a>
        </li>
        <li>
          <a href="https://www.instagram.com/evanscoltd" target="_blank">
            <img src="assets/instagram-icon.png" alt="Instagram" width="24" height="24">
          </a>
        </li>
        <li>
          <a href="https://www.linkedin.com/company/evanscoltd" target="_blank">
            <img src="assets/linkedin-icon.png" alt="LinkedIn" width="24" height="24">
          </a>
        </li>
      </ul>
    </section>

    <section id="chat-with-us">
      <h3>Chat with Us</h3>
      <p>Have questions? Chat with us on your favorite platform:</p>
      <ul>
        <li><a href="https://wa.me/254700000000" target="_blank">WhatsApp</a></li>
        <li><a href="https://m.me/evanscoltd" target="_blank">Facebook Messenger</a></li>
        <li><a href="https://t.me/evanscoltd" target="_blank">Telegram</a></li>
      </ul>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Evansco Ltd. All rights reserved.</p>
  </footer>
</body>
</html>
