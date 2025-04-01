
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>For My Cutie</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #ffe6f2;
            font-family: Arial, sans-serif;
            text-align: center;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            position: relative;
        }
        button {
            background-color: pink;
            border: none;
            padding: 15px 20px;
            font-size: 16px;
            cursor: pointer;
            border-radius: 10px;
        }
        #message {
            margin-top: 20px;
            display: none;
            font-size: 16px;
            padding: 20px;
            border-radius: 10px;
            background: #ffccdd;
            position: relative;
        }
        #message::before, #message::after {
            content: "❤️";
            font-size: 24px;
            position: absolute;
        }
        #message::before {
            top: -10px;
            left: -10px;
        }
        #message::after {
            bottom: -10px;
            right: -10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <button onclick="showMessage()">Click on the button cutie</button>
        <p id="message">❤️ You don't know that you are very special to me. When I first saw you, it felt like magic to me, as I had never seen a girl like you before. After knowing you for the last few months, I also came to realize that you are a sweet and nurturing person, and that's what I like about you so much. ❤️<br><br>
        ❤️ I know that some days of your life are very tough, but don't let them break you. Face those days and speak up for yourself. Don't let anyone control you, as I know that's the one thing you hate. I haven't spent much time alone with you, but I want to say that you are and will be the first and last girl I like in college, and my feelings for you will remain the same. ❤️<br><br>
        ❤️ There are many things that hurt me, but in the end, it is what it is. Thank you for being around me... ❤️</p>
    </div>

    <script>
        function showMessage() {
            document.getElementById('message').style.display = 'block';
        }
    </script>
</body>
</html>
