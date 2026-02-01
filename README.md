 Hola Breyon, I spent all night making this.
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
            overflow: hidden; /* So emojis don't create scrollbars */
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

        /* Emoji floating style */
        .emoji {
            position: fixed;
            font-size: 2em;
            pointer-events: none;
            user-select: none;
            animation: floatUp linear infinite;
        }

        @keyframes floatUp {
            0% { transform: translateY(100vh) rotate(0deg); opacity: 1; }
            100% { transform: translateY(-10vh) rotate(360deg); opacity: 0; }
        }
    </style>
</head>
<body>
    <h1>Ready for Fellatio February?! 💖</h1>
    <p>Click the right button and you might get what you want!</p>

    <div class="button-container">
        <button class="valentine-btn" onclick="yesbuttonAction()">Yes </button>
        <button class="valentine-btn" onclick="nobuttonAction()">No </button>
    </div>

    <script>
        const emojis = ['❤️', '🍆', '💝', '🫦', '💓', '💋', '🐻'];

        function createEmoji() {
            const emoji = document.createElement('div');
            emoji.classList.add('emoji');
            emoji.textContent = emojis[Math.floor(Math.random() * emojis.length)];
            emoji.style.left = Math.random() * 100 + 'vw';  // random horizontal start
            emoji.style.fontSize = (20 + Math.random() * 30) + 'px';  // random size
            emoji.style.animationDuration = (5 + Math.random() * 5) + 's'; // random speed

            document.body.appendChild(emoji);

            // Remove emoji after animation ends to keep DOM clean
            setTimeout(() => {
                emoji.remove();
            }, parseFloat(emoji.style.animationDuration) * 1000);
        }

        // Continuously create floating emojis
        setInterval(createEmoji, 500);

        // Button actions
        function yesbuttonAction() {
            alert("You pressed Yes! Weekly Smooches all over. 🍆🫦");
        }

        function nobuttonAction() {
            alert("You pressed No! I guess it's your turn this month.");
        }
    </script>
</body>
