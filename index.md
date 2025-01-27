<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            margin: 0;
            padding: 0;
            background: url(https://cdn.discordapp.com/attachments/1275528960314445906/1332772494414975086/0ee07d567a956d30140272704eb352f9.jpg?ex=6796789c&is=6795271c&hm=c9ac4f5f4687b6e903025e3a9427f6cdd6fd7244f773bf21ff1dedde3bd1dbb9&) no-repeat center center fixed;
            background-size: cover;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            font-family: Arial, sans-serif;
        }

        .search-bar {
            margin-bottom: 2rem;
            text-align: center;
        }

        .search-bar input[type="text"] {
            padding: 0.5rem;
            width: 300px;
            font-size: 1rem;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .search-bar input[type="submit"] {
            padding: 0.5rem 1rem;
            font-size: 1rem;
            border: none;
            border-radius: 5px;
            background-color: #4682b4;
            color: white;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .search-bar input[type="submit"]:hover {
            background-color: #5a9bd6;
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
        <div class="search-bar">
            <form action="https://www.google.com/search" method="get" target="_blank">
                <input type="text" name="q" placeholder="Search Google">
                <input type="submit" value="Search">
            </form>
        </div>
        <div class="link-container">
            <a href="https://soundcloud.com" class="link" target="_blank">SoundCloud</a>
            <a href="https://esportal.com" class="link" target="_blank">Esportal</a>
            <a href="https://twitch.tv" class="link" target="_blank">Twitch</a>
            <a href="https://youtube.com" class="link" target="_blank">YouTube</a>
            <a href="https://xplay.gg" class="link" target="_blank">Xplay.gg</a>
            <a href="https://cybershoke.net" class="link" target="_blank">Cybershoke</a>
            <a href="https://csgoskins.gg" class="link" target="_blank">SKINS</a>
            <a href="https://www.deepl.com/de/translator" class="link" target="_blank">Translator</a>
            <a href="https://cs2browser.com" class="link" target="_blank">Browser</a>
        </div>
    </main>
</body>
</html>
