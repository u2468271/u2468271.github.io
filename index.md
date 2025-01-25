<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: #000000;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            font-family: Arial, sans-serif;
        }

        .link-container {
            display: flex;
            flex-direction: column;
            gap: 1rem;
        }

        .link {
            text-decoration: none;
            color: #000000;
            background-color: #ffffff;
            padding: 1rem 2rem;
            border-radius: 5px;
            text-align: center;
            font-size: 1rem;
            transition: background-color 0.3s ease, color 0.3s ease;
        }

        .link:hover {
            background-color: #f0f0f0;
            color: #333333;
        }
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
            <a href="https://csgoskins.gg" class="link" target="_blank">CSGO SKINS</a>
            <a href="https://www.deepl.com/de/translator" class="link" target="_blank">Translator</a>
        </div>
    </main>
</body>
</html>
