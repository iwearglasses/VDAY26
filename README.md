
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
            color: #F7B2BD;
            font-size: 3em;
        }

        p {
            font-size: 1.2em;
            color: #D90368;
        }

        .button-container {
            margin-top: 40px;
        }

        .valentine-btn {
            background-color: #E34A6F;
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
        <!-- Yes Button  -->
        <button class="valentine-btn" onclick="yesbuttonAction()">Yes Button </button>

        <!-- No Button  -->
        <button class="valentine-btn" onclick="nobuttonAction()">No Button </button>
    </div>

    <script>
        function yesbuttonAction() {
            alert("You pressed Yes! Slow kissies 3xs/wk 🍆🫦");
            // You can replace alert with any custom action, like redirecting:
            // window.location.href = "https://example.com";
        }

        function nobuttonAction() {
            alert("You pressed No! I guess i'll look and not touch.");
            // Custom action for no button 
        }
    </script>
</body>
</html>
