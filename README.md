<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>

    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: Arial, sans-serif;
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
        }

        .container {
            text-align: center;
            background: rgba(255, 255, 255, 0.15);
            padding: 50px;
            border-radius: 20px;
            backdrop-filter: blur(10px);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.25);
            max-width: 600px;
            width: 90%;
        }

        h1 {
            font-size: 45px;
            margin-bottom: 15px;
        }

        p {
            font-size: 18px;
            margin-bottom: 30px;
        }

        button {
            border: none;
            padding: 14px 30px;
            font-size: 17px;
            border-radius: 10px;
            cursor: pointer;
            background: white;
            color: #667eea;
            font-weight: bold;
        }

        button:hover {
            transform: scale(1.05);
        }

        #message {
            margin-top: 25px;
            font-size: 20px;
            font-weight: bold;
        }
    </style>
</head>

<body>

    <div class="container">
        <h1>🚀 My Website</h1>

        <p>
            Welcome to my website hosted on GitHub Pages!
        </p>

        <button onclick="showMessage()">
            Click Me
        </button>

        <div id="message"></div>
    </div>

    <script>
        function showMessage() {
            document.getElementById("message").textContent =
                "🎉 It works! Your GitHub website is running!";
        }
    </script>

</body>
</html>
