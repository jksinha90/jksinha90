<!-- Careerpoint Website HTML Code -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Careerpoint - Job Updates</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f0f8ff;
      color: #333;
    }
    header {
      background-color: #00bfff;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #009acd;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 20px;
    }
    .job {
      background: white;
      padding: 15px;
      margin-bottom: 10px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    footer {
      background-color: #00bfff;
      color: white;
      text-align: center;
      padding: 10px;
    }
    .alert-form input[type=email] {
      padding: 10px;
      width: 250px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    .alert-form input[type=submit] {
      padding: 10px 20px;
      background-color: #009acd;
      border: none;
      color: white;
      border-radius: 5px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <header>
    <h1>Careerpoint</h1>
    <p>Your trusted source for Govt & Private Jobs</p>
  </header>
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About Us</a>
    <a href="#jobs">Latest Jobs</a>
    <a href="#apply">How to Apply</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="home">
    <h2>Welcome to Careerpoint</h2>
    <p>We provide up-to-date government and private job listings to help you find your next opportunity.</p>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>Careerpoint is dedicated to bringing you the latest job openings from across the country. We manually verify and post reliable job updates daily.</p>
  </section>

  <section id="jobs">
    <h2>Latest Job Listings</h2>
    <div class="job">
      <h3>Govt Job: Junior Assistant - XYZ Department</h3>
      <p>Location: Delhi | Last Date: 25-April-2025</p>
    </div>
    <div class="job">
      <h3>Private Job: Software Developer - ABC Pvt Ltd</h3>
      <p>Location: Bangalore | Last Date: 30-April-2025</p>
    </div>
  </section>

  <section id="apply">
    <h2>How to Apply</h2>
    <p>Each job listing includes an application link or contact details. Read the job description carefully and apply before the deadline.</p>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: info@careerpoint.com | Phone: +91-90000-00000</p>
    <h3>Subscribe for Job Alerts</h3>
    <form class="alert-form">
      <input type="email" placeholder="Enter your email" required />
      <input type="submit" value="Subscribe" />
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Careerpoint. All rights reserved.</p>
  </footer>
</body>
</html>
