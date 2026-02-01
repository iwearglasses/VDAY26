# VDAY26
Something cute and simple.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Valentine's Day Surprise</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #FFDEE9, #B5FFFC);
            text-align: center;
            padding: 50px;
        }

        h1 {
            color: #FF4B5C;
            font-size: 3em;
        }

        p {
            font-size: 1.2em;
            color: #333;
        }

        .button-container {
            margin-top: 40px;
        }

        .valentine-btn {
            background-color: #FF4B5C;
            color: white;
            border: none;
            padding: 15px 30px;
            margin: 10px;
            font-size: 1.2em;
            border-radius: 10px;
            cursor: pointer;
            transition: transform 0.2s, background-color 0.2s;
        }

        .valentine-btn:hover {
            transform: scale(1.1);
            background-color: #FF6B81;
        }
    </style>
</head>
<body>
    <h1>Ready for Fellatio February?! 💖</h1>
    <p>Click the right button and you might get what you want.!</p>

    <div class="button-container">
        <!-- Button 1 -->
        <button class="valentine-btn" onclick="button1Action()">Button 1</button>

        <!-- Button 2 -->
        <button class="valentine-btn" onclick="button2Action()">Button 2</button>
    </div>

    <script>
        function button1Action() {
            alert("You pressed Button 1! Slow kissies 💋");
            // You can replace alert with any custom action, like redirecting:
            // window.location.href = "https://example.com";
        }

        function button2Action() {
            alert("You pressed Button 2! 🫦🍆");
            // Custom action for button 2
        }
    </script>
</body>
</html>
