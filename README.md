<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Valentine's Day Surprise</title>
    <style>
        body {
            background-color: red;
            color: white;
            text-align: center;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .container {
            padding-top: 50px;
        }
        h1 {
            font-size: 24px;
            margin-bottom: 20px;
        }
        button {
            background-color: white;
            color: red;
            border: none;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            margin: 10px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Will you be my valentine?</h1>
        <button onclick="window.location.href = 'confirm.html';">Yes</button>
        <button onclick="window.location.href = 'retry.html';">No</button>
    </div>
</body>
</html>
