<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      align-items: flex-end;
      background-color: #87CEEB; /* Sky Blue */
      position: relative;
    }

    .sun {
      width: 100px;
      height: 100px;
      background-color: #FFD700; /* Gold */
      border-radius: 50%;
      position: absolute;
      top: 20px;
      right: 20px;
    }

    .hill {
      width: 100%;
      height: 100px;
      background-color: #228B22; /* Forest Green */
      position: absolute;
      bottom: 0;
    }

    .house {
      width: 120px;
      height: 120px;
      background-color: white; /* Chocolate */
      position: absolute;
      bottom: 100px;
      left: 50%;
      transform: translateX(-50%);
    }

    .roof {
      width: 0;
      height: 0;
      border-left: 60px solid transparent;
      border-right: 60px solid transparent;
      border-bottom: 60px solid red; /* Saddle Brown */
      position: absolute;
      top: -60px;
      left: 50%;
      transform: translateX(-50%);
    }

    .door {
      width: 30px;
      height: 50px;
      background-color: #8B4513; /* Saddle Brown */
      position: absolute;
      bottom: 0px;
      left: 50%;
      
      transform: translateX(-50%);
    }
  </style>
</head>
<body>
  <div class="sun"></div>
  <div class="hill"></div>
  <div class="house">
    <div class="roof"></div>
    <div class="door"></div>
  </div>
</body>
</html>
