# Project Responsive Web Design using Bootstrap
## Date: 16-10-2025

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Design Gallery</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f5f5f5;
    }

    header {
      background-color: #ffffff;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid #ddd;
    }

    header h1 {
      margin: 0;
      font-size: 24px;
      color: #333;
    }

    nav a {
      margin-left: 20px;
      text-decoration: none;
      color: #555;
      font-weight: 500;
    }

    .banner {
      background-color: #ffeff0;
      padding: 40px;
      text-align: center;
    }

    .banner h2 {
      margin: 0;
      font-size: 28px;
      color: #333;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      gap: 20px;
      padding: 40px;
    }

    .card {
      background-color: #fff;
      border-radius: 8px;
      overflow: hidden;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      transition: transform 0.2s ease;
    }

    .card:hover {
      transform: scale(1.02);
    }

    .card img {
      width: 100%;
      display: block;
    }

    .card-footer {
      padding: 10px 15px;
      font-size: 14px;
      color: #666;
    }
  </style>
</head>
<body>

  <header>
    <h1>Anime Gallery</h1>
    <nav>
      <a href="#">Shots</a>
      <a href="#">Designers</a>
      <a href="#">Teams</a>
      <a href="#">Community</a>
      <a href="#">Entertainment</a>
    </nav>
  </header>

  <div class="banner">
    <h2>Couples Collection💕</h2>
    <p>Priya -- Anime Lover</p>
  </div>

  <section class="gallery">
    <!-- Replace these image src values with your own image URLs -->
    <div class="card">
      <img src="https://i.pinimg.com/736x/d9/05/ea/d905ea363cdff88281002dbcce6ca82e.jpg" alt="Design 1" />
      <div class="card-footer">Lovable ❤️ Couple</div>
    </div>
    <div class="card">
      <img src="https://i.pinimg.com/736x/32/ed/21/32ed21cbc248b0743b20e965baa5b931.jpg" alt="Design 2" />
      <div class="card-footer">Himuro 💖Fuyutsuki</div>
    </div>
    <div class="card">
      <img src="https://i.pinimg.com/736x/a6/cf/30/a6cf301c20cdc01b17709ce5950a59f3.jpg" alt="Design 3" />
      <div class="card-footer">Nobita 💛 Shizuka</div>
    </div>
    <div class="card">
      <img src="https://i.pinimg.com/736x/84/19/bb/8419bbf962fa36ac95515c17a7434918.jpg" alt="Design 4" />
      <div class="card-footer">Naruto 💌 Hinata</div>
    </div>
    <div class="card">
      <img src="https://i.pinimg.com/1200x/93/b3/f1/93b3f1e3f5bbc117b9df2589437447cb.jpg" alt="Design 5" />
      <div class="card-footer">Yuki 🩶 Haru</div>
    </div>
    <div class="card">
      <img src="https://i.pinimg.com/736x/cb/44/2d/cb442d8542a1c9332c4c0fc7bd19537b.jpg" alt="Design 6" />
      <div class="card-footer">Sasukae 💗Sakura</div>
    </div>
    <!-- Add more cards as needed -->
  </section>

</body>
</html>
```
## OUTPUT:
![image  - Copy](https://github.com/user-attachments/assets/f06d9c9d-6441-43a9-8a5f-f3a6ecee1557)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
