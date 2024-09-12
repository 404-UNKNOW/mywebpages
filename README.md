<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>鸣潮 - 二次元冒险游戏</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, sans-serif;
            background-color: #f0f0f5;
            color: #333;
            margin: 0;
            padding: 20px;
        }
        header {
            text-align: center;
            padding: 20px 0;
        }
        header img {
            width: 200px;
        }
        h1 {
            font-size: 2.5em;
            color: #4a90e2;
        }
        section {
            margin-bottom: 40px;
        }
        .container {
            max-width: 900px;
            margin: auto;
        }
        .character, .screenshot {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .character img, .screenshot img {
            width: 250px;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: white;
        }
        button {
            background-color: #4a90e2;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #357ABD;
        }
    </style>
</head>
<body>

<header>
    <img src="https://placeholder.com/200" alt="鸣潮 Logo">
    <h1>鸣潮 - 探索全新的二次元世界</h1>
</header>

<div class="container">
    <section>
        <h2>游戏介绍</h2>
        <p>《鸣潮》是一款由 Project X 制作的全新二次元冒险游戏，玩家将在这个充满魔法与幻想的世界中探索未知的国度，体验独特的角色和故事。</p>
    </section>

    <section>
        <h2>热门角色</h2>
        <div class="character">
            <div>
                <img src="https://placeholder.com/250x400" alt="角色1">
                <p>角色1 - 强力战士，操控雷电之力。</p>
            </div>
            <div>
                <img src="https://placeholder.com/250x400" alt="角色2">
                <p>角色2 - 神秘法师，掌握黑暗魔法。</p>
            </div>
        </div>
    </section>

    <section>
        <h2>游戏截图</h2>
        <div class="screenshot">
            <img src="https://placeholder.com/600x400" alt="游戏截图1">
            <img src="https://placeholder.com/600x400" alt="游戏截图2">
        </div>
    </section>

    <section>
        <h2>分享游戏</h2>
        <p>与朋友分享这个美丽的世界！点击下方按钮通过 WhatsApp 分享链接。</p>
        <button onclick="shareViaWhatsApp()">分享至 WhatsApp</button>
    </section>
</div>

<footer>
    <p>鸣潮 - 官方网站 | © 2024 Project X</p>
</footer>

<script>
    function shareViaWhatsApp() {
        const url = 'https://your-game-url.com';
        const text = '快来体验二次元冒险游戏《鸣潮》！点击链接开始你的旅程: ' + url;
        const whatsappUrl = `https://api.whatsapp.com/send?text=${encodeURIComponent(text)}`;
        window.open(whatsappUrl, '_blank');
    }
</script>

</body>
</html>
# mywebpages
