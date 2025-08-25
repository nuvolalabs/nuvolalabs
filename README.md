<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sample Landing Page</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      line-height: 1.6;
      background-color: #f9fafb;
      color: #333;
    }

    header {
      background: linear-gradient(135deg, #6366f1, #3b82f6);
      color: white;
      text-align: center;
      padding: 4rem 2rem;
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: 1rem;
    }

    header p {
      font-size: 1.25rem;
      margin-bottom: 2rem;
    }

    .btn {
      background: white;
      color: #3b82f6;
      padding: 0.75rem 1.5rem;
      border: none;
      border-radius: 999px;
      font-size: 1rem;
      cursor: pointer;
      text-decoration: none;
      transition: background 0.3s, color 0.3s;
    }

    .btn:hover {
      background: #3b82f6;
      color: white;
    }

    section {
      padding: 4rem 2rem;
      max-width: 1100px;
      margin: auto;
    }

    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }

    .card {
      background: white;
      border-radius: 12px;
      padding: 2rem;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      text-align: center;
    }

    footer {
      text-align: center;
      background: #111827;
      color: #9ca3af;
      padding: 2rem;
      margin-top: 3rem;
    }

    footer a {
      color: #3b82f6;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to Our Product</h1>
    <p>Simple. Powerful. Designed to help you succeed.</p>
    <a href="#features" class="btn">Get Started</a>
  </header>

  <section id="features">
    <h2 style="text-align: center;">Why Choose Us?</h2>
    <div class="features">
      <div class="card">
        <h3>🚀 Fast</h3>
        <p>Experience lightning speed performance and seamless user interaction.</p>
      </div>
      <div class="card">
        <h3>🔒 Secure</h3>
        <p>Built with top-notch security to keep your data safe and private.</p>
      </div>
      <div class="card">
        <h3>✨ Easy to Use</h3>
        <p>Intuitive design and easy setup so you can start in minutes.</p>
      </div>
    </div>
  </section>

  <footer>
    <p>© 2025 Your Company. All rights reserved.</p>
    <p><a href="#">Privacy Policy</a> | <a href="#">Contact</a></p>
  </footer>
</body>
</html>
