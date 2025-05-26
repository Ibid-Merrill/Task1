# Task1
Loading Page
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Simple Landing Page</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <div class="container">
      <div class="logo">MyLogo</div>
      <nav>
        <ul class="nav-links">
          <li><a href="#">Home</a></li>
          <li><a href="#">Features</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section class="hero">
    <div class="container">
      <h1>Welcome to Our Landing Page</h1>
      <p>We provide solutions to make your business grow and succeed.</p>
      <a href="#" class="cta-button">Get Started</a>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2025 MyCompany. All rights reserved.</p>
      <div class="social">
        <a href="#">Facebook</a> | 
        <a href="#">Twitter</a> | 
        <a href="#">Instagram</a>
      </div>
    </div>
  </footer>
</body>
</html>

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', sans-serif;
  line-height: 1.6;
  color: #333;
}

.container {
  width: 90%;
  max-width: 1200px;
  margin: auto;
}

header {
  background: #333;
  color: #fff;
  padding: 1rem 0;
}

header .container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 1.5rem;
  font-weight: bold;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 1rem;
}

.nav-links a {
  color: #fff;
  text-decoration: none;
}

.hero {
  background: #f4f4f4;
  padding: 3rem 0;
  text-align: center;
}

.hero h1 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
}

.hero p {
  font-size: 1.2rem;
  margin-bottom: 2rem;
}

.cta-button {
  background: #007BFF;
  color: #fff;
  padding: 0.8rem 1.5rem;
  text-decoration: none;
  border-radius: 5px;
}

footer {
  background: #333;
  color: #fff;
  text-align: center;
  padding: 1.5rem 0;
  margin-top: 2rem;
}

footer .social a {
  color: #fff;
  margin: 0 0.5rem;
  text-decoration: none;
}

/* Responsive Design */
@media (max-width: 768px) {
  .nav-links {
    flex-direction: column;
    gap: 0.5rem;
  }

  header .container {
    flex-direction: column;
    align-items: flex-start;
  }

  .hero h1 {
    font-size: 2rem;
  }

  .hero p {
    font-size: 1rem;
  }
}
