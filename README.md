<!DOCTYPE html>
<html lang="zh">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>下载我的APP</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Arial', sans-serif;
      background: linear-gradient(to right, #3a6186, #89253e);
      color: white;
      text-align: center;
      display: flex;
      flex-direction: column;
      justify-content: center;
      height: 100vh;
    }
    h1 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }
    p {
      margin-bottom: 2rem;
    }
    a.download-btn {
      background-color: white;
      color: #89253e;
      padding: 1rem 2rem;
      border-radius: 999px;
      font-weight: bold;
      text-decoration: none;
      transition: background-color 0.3s;
    }
    a.download-btn:hover {
      background-color: #f0f0f0;
    }
    footer {
      position: absolute;
      bottom: 20px;
      width: 100%;
      font-size: 0.8rem;
      color: #ccc;
    }
  </style>
</head>
<body>
  <h1>欢迎体验我的APP</h1>
  <p>这是一个极简、实用的APP，快来下载试试！</p>
  <a class="download-btn" href="your_app.apk" download>立即下载</a>
  <footer>
    Made with passion by 你的小李总
  </footer>
</body>
</html>
