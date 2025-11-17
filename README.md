# hjj76.github.io
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Pages 测试页面</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', 'Microsoft YaHei', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            margin: 0;
            padding: 20px;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .container {
            background: white;
            padding: 50px;
            border-radius: 20px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            text-align: center;
            max-width: 600px;
            width: 90%;
        }
        
        h1 {
            color: #333;
            font-size: 2.5em;
            margin-bottom: 20px;
        }
        
        p {
            color: #666;
            font-size: 1.2em;
            line-height: 1.6;
            margin-bottom: 15px;
        }
        
        .success {
            color: #28a745;
            font-weight: bold;
            font-size: 1.3em;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🎉 GitHub Pages 测试成功！</h1>
        <p class="success">恭喜！你的网站已成功部署</p>
        <p>这是我的第一个 GitHub Pages 网站</p>
        <p>通过这个实验，我学会了如何部署静态网站</p>
        <p>网站地址：https://hj176.github.io/</p>
        <p>部署时间：<span id="current-time"></span></p>
    </div>

    <script>
        // 显示当前时间
        const now = new Date();
        document.getElementById('current-time').textContent = now.toLocaleString();
    </script>
</body>
</html>
