<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            margin: 0;
            padding: 0;
            background: url('your-image-url.jpg') no-repeat center center fixed;
            background-size: cover;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            font-family: Arial, sans-serif;
        }

        .link-container {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 1rem;
            text-align: center;
            width: 80%;
        }

        .link {
            text-decoration: none;
            color: #000000;
            background-color: #ffffff;
            padding: 1rem;
            border-radius: 5px;
            font-size: 1rem;
            transition: background-color 0.3s ease, color 0.3s ease;
        }

        .link:hover {
            background-color: #f0f0f0;
            color: #333333;
        }

        .link:nth-child(1) { background-color: #ff6347; color: white; }
        .link:nth-child(2) { background-color: #4682b4; color: white; }
        .link:nth-child(3) { background-color: #32cd32; color: white; }
        .link:nth-child(4) { background-color: #ffa500; color: white; }
        .link:nth-child(5) { background-color: #8a2be2; color: white; }
        .link:nth-child(6) { background-color: #d2691e; color: white; }
        .link:nth-child(7) { background-color: #5f9ea0; color: white; }
        .link:nth-child(8) { background-color: #ff1493; color: white; }
    </style>
</head>
<body>
    <main>
        <div class="link-container">
            <a href="https://soundcloud.com" class="link" target="_blank">SoundCloud</a>
            <a href="https://esportal.com" class="link" target="_blank">Esportal</a>
            <a href="https://twitch.tv" class="link" target="_blank">Twitch</a>
            <a href="https://youtube.com" class="link" target="_blank">YouTube</a>
            <a href="https://xplay.gg" class="link" target="_blank">Xplay.gg</a>
            <a href="https://cybershoke.net" class="link" target="_blank">Cybershoke</a>
            <a href="https://csgoskins.gg" class="link" target="_blank">SKINS</a>
            <a href="https://www.deepl.com/de/translator" class="link" target="_blank">Translator</a>
        </div>
    </main>
</body>
</html>
