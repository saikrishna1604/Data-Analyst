<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Button to Open New Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 50px;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <h1>Welcome to My Page</h1>
    <button onclick="openNewPage()">Click Me to Open Another Page</button>

    <script>
        function openNewPage() {
            // Open a new page (replace 'newpage.html' with your target page)
            window.open('Descritive', '_blank'); // '_blank' opens it in a new tab
        }
    </script>
</body>
</html>
