<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Image Gallery</title>
<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        text-align: center;
    }
    .container {
        position: relative;
        max-width: 800px;
        margin: 0 auto;
        padding: 20px;
    }
    .image {
        max-width: 100%;
        height: auto;
    }
    .arrow {
        position: absolute;
        bottom: 10px;
        width: 40px;
        height: 40px;
        background-color: black;
        color: white;
        font-size: 24px;
        line-height: 40px;
        cursor: pointer;
    }
    .arrow.left {
        left: 10px;
    }
    .arrow.right {
        right: 10px;
    }
    .logo {
        position: absolute;
        top: 10px;
        left: 50%;
        transform: translateX(-50%);
        max-width: 100px;
        height: auto;
    }
</style>
</head>
<body>
<div class="container">
    <img class="image" src="big-image.jpg" alt="Big Image">
    <img class="logo" src="logo.png" alt="Logo">
    <div class="arrow left">&#9664;</div>
    <div class="arrow right">&#9654;</div>
</div>
</body>
</html>
