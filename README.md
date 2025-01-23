<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Video</title>
    <style>
        body {
            font-family: 'Courier New', monospace, sans-serif;
            margin: 0;
            padding: 0;
            background: radial-gradient(circle, rgba(0, 0, 0, 1) 0%, rgba(0, 0, 0, 0.85) 50%, rgba(0, 0, 0, 0.7) 100%);
            background-size: cover;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            color: #ffd700; /* Gold */
            text-align: center;
            background-image: url('https://www.transparenttextures.com/patterns/black-marble.png'); /* Add a marble texture */
        }
        .container {
            background: rgba(0, 0, 0, 0.8);
            padding: 30px;
            border-radius: 20px;
            box-shadow: 0 5px 30px rgba(0, 0, 0, 0.7);
            border: 3px solid gold;
            background-image: linear-gradient(45deg, rgba(0, 0, 0, 0.8) 25%, rgba(255, 215, 0, 0.8) 25%, rgba(255, 215, 0, 0.8) 50%, rgba(0, 0, 0, 0.8) 50%, rgba(0, 0, 0, 0.8) 75%, rgba(255, 215, 0, 0.8) 75%, rgba(255, 215, 0, 0.8) 100%);
            background-size: 50px 50px;
        }
        video {
            width: 100%;
            max-width: 600px;
            border: 6px solid;
            border-image-source: linear-gradient(to right, #000, #ffd700, #000);
            border-image-slice: 1;
            border-radius: 15px;
            margin-top: 20px;
        }
        h1, p {
            font-size: 2rem;
            text-align: center;
            background: linear-gradient(to right, #ffd700, #000);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: sparkle 3s infinite;
        }
        h1 {
            font-size: 2.8rem;
            margin-bottom: 20px;
        }
        p {
            font-size: 1.5rem;
            margin-top: 15px;
        }
        @keyframes sparkle {
            0%, 100% {
                background-position: 0 0;
            }
            50% {
                background-position: 200% 0;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Happy Birthday, Agent Aldi!</h1>
        <video controls>
            <source src="https://github.com/dinaapk/dina-ishungry/blob/main/Alay.MOV" type="video/MOV">
            <source src="Alay_video.webm](https://github.com/dinaapk/dina-ishungry/blob/main/Alay.MOV" type="video/webm">
            Your browser does not support the video tag.
        </video>
        <p>Love you, moron.</p>
    </div>
</body>
</html>
