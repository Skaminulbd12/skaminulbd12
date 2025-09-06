<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>MyTube</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f9f9f9;
    }
    header {
      background-color: #202020;
      color: white;
      display: flex;
      align-items: center;
      padding: 10px 20px;
    }
    header .logo {
      font-size: 24px;
      font-weight: bold;
      margin-right: 30px;
    }
    header input {
      flex: 1;
      padding: 8px;
      font-size: 16px;
      border-radius: 2px;
      border: none;
    }
    header .login {
      margin-left: 20px;
      color: white;
      text-decoration: none;
    }
    .videos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .video-card {
      background: white;
      border-radius: 6px;
      overflow: hidden;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    .video-card img {
      width: 100%;
    }
    .video-card .info {
      padding: 10px;
    }
    .video-card .info h4 {
      margin: 0;
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">MyTube</div>
    <input type="text" placeholder="Search" />
    <a href="#" class="login">Login</a>
  </header>

  <div class="videos">
    <div class="video-card">
      <img src="https://via.placeholder.com/300x170" alt="Video thumbnail" />
      <div class="info">
        <h4>Sample Video Title</h4>
        <p>1.2M views · 1 week ago</p>
      </div>
    </div>
    <div class="video-card">
      <img src="https://via.placeholder.com/300x170" alt="Video thumbnail" />
      <div class="info">
        <h4>Another Video</h4>
        <p>500K views · 2 days ago</p>
      </div>
    </div>
    <!-- আরও ভিডিও কার্ড কপি করে বসানো যাবে -->
  </div>

</body>
</html>
