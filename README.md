<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Image and Buttons</title>
  <style>
    /* Add some basic styling for the layout */
    body {
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
      margin: 0;
    }
    .container {
      display: flex;
      align-items: center;
    }
    .image-container {
      flex: 1;
      padding-right: 20px;
    }
    .buttons-container {
      display: flex;
      flex-direction: column;
    }
    .button {
      margin-bottom: 10px;
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Image on the left side -->
    <div class="image-container">
      <img src="9 (1).jpg" alt="Image 9 (1)">
    </div>

    <!-- Buttons on the right side -->
    <div class="buttons-container">
      <button class="button">Button 1</button>
      <button class="button">Button 2</button>
      <button class="button">Button 3</button>
      <button class="button">Button 4</button>
    </div>
  </div>
</body>
</html>
