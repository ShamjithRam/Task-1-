<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Landing Page</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Welcome to Our Site</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">About</a>
      <a href="#">Services</a>
      <a href="#">Contact</a>
    </nav>
  </header>
  <section class="hero">
    <h2>Your Next Adventure Awaits</h2>
    <button>Get Started</button>
  </section>
  <footer>
    <p>&copy; 2025 All rights reserved</p>
  </footer>
</body>
</html>
body {
  margin: 0;
  font-family: Arial, sans-serif;
}
header {
  display: flex;
  justify-content: space-between;
  padding: 20px;
  background: #333;
  color: white;
}
nav a {
  color: white;
  margin-left: 15px;
  text-decoration: none;
}
.hero {
  text-align: center;
  padding: 100px 20px;
  background: url('hero-image.jpg') center/cover no-repeat;
  color: white;
}
button {
  padding: 10px 20px;
  background: #ff6347;
  border: none;
  color: white;
  cursor: pointer;
}
footer {
  text-align: center;
  padding: 10px;
  background: #333;
  color: white;
}
