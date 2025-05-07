<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>给牧野的专属告白信 💖</title>
    <style>
        / 通用样式 /
        body {
            background: linear-gradient(135deg, #ff9a9e, #fad0c4);
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0;
            font-family: '楷体', cursive;
            padding: 15px; / 手机安全边距 /
        }

        / 告白盒子 /
        .love-box {
            background: rgba(255, 255, 255, 0.96);
            padding: 1.5rem;
            border-radius: 18px;
            box-shadow: 0 0 25px rgba(255, 105, 180, 0.35);
            text-align: center;
            animation: heartbeat 1.5s infinite;
            max-width: 95%; / 手机适配 /
        }

        / 图片样式 /
        .love-photo {
            width: 240px;           / 默认显示尺寸 /
            max-width: 90%;         / 小屏自适应 /
            border-radius: 12px;    / 圆角程度 /
            border: 3px solid #ff69b4;
            box-shadow: 0 8px 25px rgba(255, 105, 180, 0.3);
            margin: 15px auto;
            transition: all 0.3s ease;
        }

        / 图片悬停效果 /
        .love-photo:hover {
            transform: scale(1.03);
            box-shadow: 0 10px 30px rgba(255, 105, 180, 0.4);
        }

        / 文字样式 /
        h1 {
            color: #ff1493;
            margin: 1rem 0;
            font-size: 2.1rem;
            line-height: 1.3;
        }

        / 签名样式 /
        .signature {
            color: #666;
            margin-top: 1.2rem;
            font-style: italic;
            font-size: 1.1rem;
        }

        / 心跳动画 /
        @keyframes heartbeat {
            0% { transform: scale(1); }
            50% { transform: scale(1.03); }
            100% { transform: scale(1); }
        }
    </style>
</head>
<body>
    <div class="love-box">
        <!-- 核心图片 -->
        <img src="muye-phono.jpg" 
             alt="牧野的珍贵照片"
             class="love-photo"
             onerror="this.style.display='none'"> <!-- 图片加载失败时自动隐藏 -->

        <h1>牧野，你是我心动的唯一理由！💞</h1>
        <h1>Muye, You Make My Heart Beat! 💘</h1>
        
        <p class="signature">
            —— 古吉的真心日月可鉴 🌟<br>
            ✧٩(ˊωˋ*)و✧
        </p>
    </div>
</body>
</html>
