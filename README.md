<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Simple Web Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #eef2f3;
      color: #333;
      margin: 0;
      padding: 20px;
      text-align: center;
    }
    h1 {
      color: #2a9d8f;
      margin-bottom: 10px;
    }
    p {
      font-size: 18px;
      margin-bottom: 30px;
      max-width: 600px;
      margin-left: auto;
      margin-right: auto;
    }
    button {
      background-color: #e76f51;
      color: white;
      border: none;
      padding: 12px 24px;
      font-size: 16px;
      border-radius: 5px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }
    button:hover {
      background-color: #d65a3e;
    }
  </style>
</head>
<body>

  <h1>Welcome to My Page</h1>
  <p>This page demonstrates a basic webpage layout with HTML, CSS styling, and JavaScript interaction.</p>
  
  <button id="myButton">Click Me!</button>

  <script>
    document.getElementById('myButton').addEventListener('click', function() {
      alert('Hello! Thanks for clicking the button.');
    });
  </script>

</body>
</html>
