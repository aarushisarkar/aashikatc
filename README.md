<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Will Aashi Get Her TC?</title>
  <style>
    body {
      background-color: #cce7ff;
      font-family: Arial, sans-serif;
      text-align: center;
      padding-top: 100px;
    }

    h1 {
      color: #003366;
      font-size: 2.5rem;
    }

    button {
      margin: 20px;
      padding: 15px 30px;
      font-size: 1.2rem;
      background-color: #ffffff;
      border: 2px solid #003366;
      border-radius: 10px;
      cursor: pointer;
      transition: all 0.3s ease;
    }

    button:hover {
      background-color: #003366;
      color: white;
    }

    #response {
      margin-top: 40px;
      font-size: 1.8rem;
      color: #003366;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <h1>Will Aashi get her TC?</h1>
  <button onclick="respondYes()">Yes</button>
  <button onclick="respondNo()">No</button>

  <div id="response"></div>

  <script>
    function respondYes() {
      document.getElementById('response').textContent = "Nope, u still won't 😭";
    }

    function respondNo() {
      document.getElementById('response').textContent = "Exactly 😤";
    }
  </script>
</body>
</html>
