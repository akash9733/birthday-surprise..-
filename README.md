!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anisha's Birthday Surprise</title>
    <style>
        /* General page settings */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: radial-gradient(circle, rgba(255, 204, 255, 1) 0%, rgba(255, 153, 204, 1) 100%);
        }

        .content {
            text-align: center;
            background-color: rgba(0, 0, 0, 0.7);
            color: white;
            padding: 40px;
            border-radius: 25px;
            box-shadow: 0 4px 40px rgba(0, 0, 0, 0.5);
            width: 80%;
            max-width: 600px;
        }

        h1 {
            font-size: 50px;
            margin: 0 0 20px;
            font-weight: 600;
            color: #ff69b4;
        }

        p {
            font-size: 20px;
            font-style: italic;
            margin-bottom: 30px;
            color: #ffe4e1;
        }

        /* Button styling */
        .button {
            background-color: #ff69b4;
            color: white;
            font-size: 20px;
            padding: 18px 50px;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            text-decoration: none;
            transition: all 0.3s ease;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }

        .button:hover {
            background-color: #e157a2;
            transform: translateY(-4px);
        }

        .button:active {
            background-color: #e14892;
            transform: translateY(2px);
        }

        /* Confetti animation (celebration effect) */
        .confetti {
            position: fixed;
            top: 0;
            left: 0;
            pointer-events: none;
            width: 100%;
            height: 100%;
            z-index: 9999;
            display: none; /* Hidden by default */
        }

        @keyframes confettiAnimation {
            0% {
                transform: translateY(-100px) rotate(0deg);
            }
            100% {
                transform: translateY(100vh) rotate(360deg);
            }
        }

        .confetti .piece {
            position: absolute;
            top: 0;
            width: 10px;
            height: 10px;
            background-color: #ff69b4;
            animation: confettiAnimation 3s linear infinite;
        }

        /* Generate random confetti pieces */
        .confetti .piece:nth-child(1) {
            left: 10%;
            animation-delay: 0s;
        }

        .confetti .piece:nth-child(2) {
            left: 20%;
            animation-delay: 1s;
        }

        .confetti .piece:nth-child(3) {
            left: 30%;
            animation-delay: 2s;
        }

        .confetti .piece:nth-child(4) {
            left: 40%;
            animation-delay: 0.5s;
        }

        .confetti .piece:nth-child(5) {
            left: 50%;
            animation-delay: 1.5s;
        }

        .confetti .piece:nth-child(6) {
            left: 60%;
            animation-delay: 2.5s;
        }

        /* Footer message */
        .footer {
            margin-top: 30px;
            font-size: 18px;
            color: #ffe4e1;
        }
    </style>
</head>
<body>
    <div class="content">
        <h1>Happy Birthday, Anisha!</h1>
        <p>Here's a special surprise just for you!</p>
        <a href="YOUR_GIFT_CARD_LINK" class="button" id="giftBtn" target="_blank">Claim Your Gift Card</a>
        <div class="footer">
            <p>Wishing you a day full of joy and love! 🎉</p>
        </div>
    </div>

    <!-- Confetti Effect -->
    <div class="confetti" id="confettiContainer">
        <div class="piece"></div>
        <div class="piece"></div>
        <div class="piece"></div>
        <div class="piece"></div>
        <div class="piece"></div>
        <div class="piece"></div>
    </div>

    <script>
        document.getElementById('giftBtn').addEventListener('click', function() {
            // Show the confetti effect
            document.getElementById('confettiContainer').style.display = 'block';

            // Optionally, hide the confetti after a few seconds
            setTimeout(() => {
                document.getElementById('confettiContainer').style.display = 'none';
            }, 8000); // Hide after 8 seconds
        });
    </script>
</body>
</html>
 !DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anisha's Birthday Surprise</title>
    <style>
        /* General page settings */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: radial-gradient(circle, rgba(255, 204, 255, 1) 0%, rgba(255, 153, 204, 1) 100%);
        }

        .content {
            text-align: center;
            background-color: rgba(0, 0, 0, 0.7);
            color: white;
            padding: 40px;
            border-radius: 25px;
            box-shadow: 0 4px 40px rgba(0, 0, 0, 0.5);
            width: 80%;
            max-width: 600px;
        }

        h1 {
            font-size: 50px;
            margin: 0 0 20px;
            font-weight: 600;
            color: #ff69b4;
        }

        p {
            font-size: 20px;
            font-style: italic;
            margin-bottom: 30px;
            color: #ffe4e1;
        }

        /* Button styling */
        .button {
            background-color: #ff69b4;
            color: white;
            font-size: 20px;
            padding: 18px 50px;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            text-decoration: none;
            transition: all 0.3s ease;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }

        .button:hover {
            background-color: #e157a2;
            transform: translateY(-4px);
        }

        .button:active {
            background-color: #e14892;
            transform: translateY(2px);
        }

        /* Confetti animation (celebration effect) */
        .confetti {
            position: fixed;
            top: 0;
            left: 0;
            pointer-events: none;
            width: 100%;
            height: 100%;
            z-index: 9999;
            display: none; /* Hidden by default */
        }

        @keyframes confettiAnimation {
            0% {
                transform: translateY(-100px) rotate(0deg);
            }
            100% {
                transform: translateY(100vh) rotate(360deg);
            }
        }

        .confetti .piece {
            position: absolute;
            top: 0;
            width: 10px;
            height: 10px;
            background-color: #ff69b4;
            animation: confettiAnimation 3s linear infinite;
        }

        /* Generate random confetti pieces */
        .confetti .piece:nth-child(1) {
            left: 10%;
            animation-delay: 0s;
        }

        .confetti .piece:nth-child(2) {
            left: 20%;
            animation-delay: 1s;
        }

        .confetti .piece:nth-child(3) {
            left: 30%;
            animation-delay: 2s;
        }

        .confetti .piece:nth-child(4) {
            left: 40%;
            animation-delay: 0.5s;
        }

        .confetti .piece:nth-child(5) {
            left: 50%;
            animation-delay: 1.5s;
        }

        .confetti .piece:nth-child(6) {
            left: 60%;
            animation-delay: 2.5s;
        }

        /* Footer message */
        .footer {
            margin-top: 30px;
            font-size: 18px;
            color: #ffe4e1;
        }
    </style>
</head>
<body>
    <div class="content">
        <h1>Happy Birthday, Anisha!</h1>
        <p>Here's a special surprise just for you!</p>
        <a href="YOUR_GIFT_CARD_LINK" class="button" id="giftBtn" target="_blank">Claim Your Gift Card</a>
        <div class="footer">
            <p>Wishing you a day full of joy and love! 🎉</p>
        </div>
    </div>

    <!-- Confetti Effect -->
    <div class="confetti" id="confettiContainer">
        <div class="piece"></div>
        <div class="piece"></div>
        <div class="piece"></div>
        <div class="piece"></div>
        <div class="piece"></div>
        <div class="piece"></div>
    </div>

    <script>
        document.getElementById('giftBtn').addEventListener('click', function() {
            // Show the confetti effect
            document.getElementById('confettiContainer').style.display = 'block';

            // Optionally, hide the confetti after a few seconds
            setTimeout(() => {
                document.getElementById('confettiContainer').style.display = 'none';
            }, 8000); // Hide after 8 seconds
        });
    </script>
</body>
</html>
# birthday-surprise..-html
