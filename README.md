# Birthday-card
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: url('https://source.unsplash.com/1600x900/?birthday,party') no-repeat center center/cover;
            text-align: center;
            color: white;
            font-family: Arial, sans-serif;
        }
        .container {
            background: rgba(0, 0, 0, 0.6);
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 0 10px rgba(255, 255, 255, 0.5);
        }
        h1 {
            font-size: 50px;
            animation: fadeIn 2s ease-in-out;
        }
        p {
            font-size: 20px;
            animation: fadeIn 3s ease-in-out;
        }
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🎉 Happy Birthday My Love! 🎂</h1>
        <p>Wishing you a day filled with love, joy, and laughter!</p>
    </div>
</body>
</html>
