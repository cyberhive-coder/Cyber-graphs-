# Cyber-graphs-
1. HTML Code

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Graphic Design Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      color: #333;
      margin: 0;
      padding: 0;
    }
    header {
      background: #000;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
      padding: 20px;
    }
    .gallery img {
      width: 100%;
      border-radius: 10px;
    }
    footer {
      background: #222;
      color: white;
      text-align: center;
      padding: 10px;
      font-size: 14px;
    }
  </style>
</head>
<body>

  <header>
    <h1>My Graphic Design Portfolio</h1>
    <p>Explore my work below</p>
  </header>

  <section class="gallery">
    <img src="your-image1.jpg" alt="Design 1" />
    <img src="your-image2.jpg" alt="Design 2" />
    <img src="your-image3.jpg" alt="Design 3" />
    <!-- Add more images as needed -->
  </section>

  <footer>
    &copy; 2025 Your Name | All rights reserved
  </footer>

</body>
</html>
