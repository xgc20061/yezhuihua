<!DOCTYPE html>  
<html lang="zh-CN">  
<head>  
    <meta charset="UTF-8">  
    <title>小明的旅行日记</title>  
    <style>  
        body {  
            font-family: 'Arial', sans-serif;  
            background-color: #f0f4f8;  
            color: #333;  
            line-height: 1.6;  
            margin: 0;  
            padding: 20px;  
        }  
        .container {  
            max-width: 800px;  
            margin: auto;  
            background-color: white;  
            padding: 30px;  
            box-shadow: 0 0 10px rgba(0,0,0,0.1);  
        }  
        .header {  
            text-align: center;  
            background-color: #4a90e2;  
            color: white;  
            padding: 20px;  
        }  
        .navigation {  
            background-color: #e6f2ff;  
            padding: 10px;  
            text-align: center;  
        }  
        .content {  
            margin-top: 20px;  
        }  
        img {  
            max-width: 100%;  
            height: auto;  
            border-radius: 10px;  
        }  
    </style>  
</head>  
<body>  
    <div class="container">  
        <div class="header">  
            <h1>🌍 小明的旅行日记</h1>  
        </div>  
        
        <div class="navigation">  
            <a href="#home">首页</a> |   
            <a href="#destinations">旅行目的地</a> |   
            <a href="#photos">照片集</a> |   
            <a href="#music">旅行音乐</a>  
        </div>  
        
        <div class="content">  
            <h2 id="home">最新旅行 - 大理古城</h2>  
            <img src="https://pic.baidu.com/dali.jpg" alt="大理古城">  
            
            <p>在这里，我邂逅了最美的风景和最纯粹的生活。大理的悠闲生活、古朴建筑和洱海的壮丽景色，让我深深地爱上了这座城市。</p>  
            
            <h3>精彩推荐</h3>  
            <ul>  
                <li><a href="https://www.dali.cn" target="_blank">大理旅游官网</a></li>  
                <li><a href="music/dali_song.mp3">大理旅行音乐</a></li>  
            </ul>  
            
            <h3>旅行视频</h3>  
            <video width="100%" controls>  
                <source src="travel_video.mp4" type="video/mp4">  
                您的浏览器不支持视频播放  
            </video>  
        </div>  
        
        <div class="navigation">  
            <a href="#home">返回顶部</a>  
        </div>  
    </div>  
</body>  
</html>
