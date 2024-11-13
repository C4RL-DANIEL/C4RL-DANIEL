<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Carlify</title>
  <style>
    /* Resetting some default styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    /* Body style */
    body {
      color: #333;
      background-color: #f4f4f9;
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
    }

    /* Navbar style */
    .navbar {
      width: 100%;
      padding: 15px 30px;
      background-color: #4A90E2;
      color: #fff;
      text-align: left;
    }

    .navbar h1 {
      font-size: 2em;
      font-weight: bold;
      cursor: pointer;
    }

    /* Hero section style */
    .hero {
      width: 100%;
      padding: 80px 30px;
      background-color: #e1ecf4;
    }

    .hero h2 {
      font-size: 3em;
      margin-bottom: 10px;
      color: #4A90E2;
    }

    .hero p {
      font-size: 1.2em;
      margin-bottom: 30px;
      color: #333;
    }

    .hero button {
      padding: 15px 30px;
      font-size: 1em;
      color: #fff;
      background-color: #4A90E2;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: background-color 0.3s;
    }

    .hero button:hover {
      background-color: #357ABD;
    }

    /* Features section style */
    .features {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      padding: 50px 30px;
      max-width: 1200px;
    }

    .feature-card {
      width: 280px;
      margin: 15px;
      padding: 30px;
      background-color: #fff;
      box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
      border-radius: 10px;
      transition: transform 0.3s;
    }

    .feature-card:hover {
      transform: translateY(-5px);
    }

    .feature-card h3 {
      font-size: 1.5em;
      margin-bottom: 10px;
      color: #4A90E2;
    }

    .feature-card p {
      font-size: 1em;
      color: #666;
    }

    /* Footer style */
    .footer {
      width: 100%;
      padding: 20px;
      background-color: #4A90E2;
      color: #fff;
      font-size: 0.9em;
      text-align: center;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <div class="navbar">
    <h1>Carlify</h1>
  </div>

  <!-- Hero Section -->
  <section class="hero">
    <h2>Welcome to Carlify</h2>
    <p>Your journey to personal growth and community connection starts here.</p>
    <button>Get Started</button>
  </section>

  <!-- Features Section -->
  <section class="features">
    <div class="feature-card">
      <h3>Community Hub</h3>
      <p>Connect with like-minded individuals and explore engaging discussions.</p>
    </div>
    <div class="feature-card">
      <h3>Business Support</h3>
      <p>Discover and support local businesses right in your area.</p>
    </div>
    <div class="feature-card">
      <h3>Personal Growth</h3>
      <p>Access self-improvement resources to help you reach your goals.</p>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <p>&copy; 2024 Carlify. All rights reserved.</p>
  </footer>

</body>
</html>
