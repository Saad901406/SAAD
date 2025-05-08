<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Saad's Personal Webpage</title>
  <style>
    body {
      background: linear-gradient(to right, #83a4d4, #b6fbff);
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      text-align: center;
      animation: fadeIn 2s ease-in;
    }

    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }

    header {
      background-color: #004080;
      color: white;
      padding: 20px 0;
      animation: slideDown 1s ease-out;
    }

    @keyframes slideDown {
      from {transform: translateY(-100%);}
      to {transform: translateY(0);}
    }

    img {
      border-radius: 50%;
      width: 150px;
      margin-top: 20px;
      animation: zoomIn 1s ease-in-out;
    }

    @keyframes zoomIn {
      from {transform: scale(0);}
      to {transform: scale(1);}
    }

    .content {
      padding: 30px;
    }

    .card {
      background-color: white;
      max-width: 500px;
      margin: auto;
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
      animation: floatUp 1.5s ease-in-out;
    }

    @keyframes floatUp {
      from {transform: translateY(100px); opacity: 0;}
      to {transform: translateY(0); opacity: 1;}
    }

    footer {
      background-color: #004080;
      color: white;
      padding: 10px;
      position: fixed;
      width: 100%;
      bottom: 0;
      animation: fadeIn 2s ease-in;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to saad's World!</h1>
  </header>

  <div class="content">
    <div class="card">
      <img src="https://via.placeholder.com/150" alt="saad's photo">
      <h2>saad Shaikh </h2>
      <p>Hi! I'm a student of Class 7A at OLIV Orchid International School. I love adventure, stories, and learning cool things—just like scientists and exploring!</p>
      <p><strong>Hobbies:</strong> Acting, stunts, exploring, and storytelling.</p>
      <p><strong>Dream:</strong> To become a hero like veer!</p>
      <p><strong>Email:</strong> ssaaad7860@gmail.com</p>
    </div>
  </div>

  <footer>
    &copy; 2025 Saad | All rights reserved
  </footer>

</body>
</html>