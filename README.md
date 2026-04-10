<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>QR Code Generator</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <div class="container">
    <h1>QR Code Generator</h1>

    <!-- Input -->
    <input type="text" id="qrText" placeholder="Enter text or URL">
    <button onclick="generateQR()">Generate QR</button>

    <!-- QR Output -->
    <div id="imgBox">
      <img id="qrImage" src="">
    </div>

    <!-- Clickable Preview Image -->
    <div class="preview">
      <a href="https://qr-code-generator-using-html-css-ja.vercel.app/" target="_blank">
        <img src="preview.png" alt="Live Preview">
      </a>
      <p>Click image to open live site</p>
    </div>

  </div>

<script src="script.js"></script>
</body>
</html>
