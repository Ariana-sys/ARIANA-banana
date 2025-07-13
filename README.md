# ARIANA-banana
git remote add origin https://github.com/Ariana-sys/ARIANA-banana.git
git branch -M main
git push -u origin main
<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <title>Fußbilder Galerie</title>
  <style>
    body {
      background-color: #f9f4f0;
      font-family: sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background: #f4c2c2;
      padding: 20px;
      text-align: center;
    }
    h1 {
      margin: 0;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 15px;
      padding: 20px;
    }
    .gallery img {
      width: 100%;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.2);
    }
  </style>
</head>
<body>

<header>
  <h1>👣 Fußbilder Galerie</h1>
  <p>Einfach ansehen, ohne Anmeldung</p>
</header>

<section class="gallery">
  <img src="https://via.placeholder.com/300x300?text=Fu%C3%9F+1" alt="Fuß 1">
  <img src="https://via.placeholder.com/300x300?text=Fu%C3%9F+2" alt="Fuß 2">
  <img src="https://via.placeholder.com/300x300?text=Fu%C3%9F+3" alt="Fuß 3">
  <img src="https://via.placeholder.com/300x300?text=Fu%C3%9F+4" alt="Fuß 4">
</section>

</body>
</html>
