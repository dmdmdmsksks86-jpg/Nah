<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <title>Nah Hub</title>
  <style>
    body {
      background: #111;
      color: white;
      text-align: center;
      margin-top: 100px;
      font-family: Arial;
    }
    button {
      padding: 12px 25px;
      font-size: 20px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <h1>Nah Hub</h1>
  <p>Nhấn để copy script</p>

  <button onclick="navigator.clipboard.writeText('loadstring(game:HttpGet(\"https://example.com/nahhub.lua\"))()')">
    Copy Script
  </button>
</body>
</html>
