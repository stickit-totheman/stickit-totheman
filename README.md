<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Homestuck Comic Menu</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f0f0;
      margin: 0;
      padding: 0;
      text-align: center; /* Center align for the image box */
    }
    .menu {
      background-color: #333;
      color: #fff;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 10px 20px;
    }
    .menu ul {
      list-style-type: none;
      margin: 0;
      padding: 0;
      display: flex;
    }
    .menu ul li {
      margin-right: 20px;
    }
    .menu ul li a {
      color: #fff;
      text-decoration: none;
      font-size: 16px;
      transition: color 0.3s;
    }
    .menu ul li a:hover {
      color: #99ccff;
    }
    .image-box {
      margin-top: 20px;
    }
    .image-box img {
      max-width: 100%;
      height: auto;
    }
  </style>
</head>
<body>

<div class="menu">
  <div class="logo">
    <img src="path_to_your_logo_image.png" alt="Homestuck Logo" height="40">
  </div>
  <ul>
    <li><a href="#">ARCHIVE</a></li>
    <li><a href="#">BEGIN READING</a></li>
    <li><a href="#">LATEST UPDATE</a></li>
    <li><a href="#">SUGGESTIONS</a></li>
    <li><a href="#">CAST</a></li>
    <li><a href="#">AUTHORS</a></li>
    <li><a href="#">RSS</a></li>
  </ul>
</div>

<div class="image-box">
  <img src="path_to_your_image.png" alt="Homestuck Image Box">
</div>

</body>
</html>
