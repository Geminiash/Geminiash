<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>动漫推荐收藏</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #1a1a2e 0%, #16213e 50%, #0f3460 100%);
            color: #e6e6e6;
            line-height: 1.6;
            padding: 20px;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        header {
            text-align: center;
            padding: 40px 0;
            margin-bottom: 40px;
        }
        
        h1 {
            font-size: 3rem;
            margin-bottom: 10px;
            background: linear-gradient(90deg, #ff6b6b, #ffa36c, #ffde7d);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        
        .anime-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
            gap: 30px;
            margin-bottom: 50px;
        }
        
        .anime-card {
            background: rgba(30, 30, 46, 0.8);
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease;
        }
        
        .anime-card:hover {
            transform: translateY(-5px);
        }
        
        .anime-image {
            width: 100%;
            height: 320px;
            background: #2d3748;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #a0aec0;
            font-size: 1.2rem;
        }
        
        .anime-info {
            padding: 20px;
        }
        
        .anime-title {
            font-size: 1.2rem;
            font-weight: bold;
            margin-bottom: 10px;
            color: #ffde7d;
        }
        
        .anime-desc {
            font-size: 0.9rem;
            color: #b8b8b8;
            margin-bottom: 15px;
        }
        
        .anime-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 5px;
        }
        
        .tag {
            background: rgba(106, 152, 240, 0.2);
            color: #6a98f0;
            padding: 3px 8px;
            border-radius: 20px;
            font-size: 0.8rem;
        }
        
        footer {
            text-align: center;
            padding: 30px 0;
            margin-top: 50px;
            color: #888;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>动漫推荐收藏</h1>
            <p>精心挑选的优质动漫作品</p>
        </header>
        
        <div class="anime-grid">
            <div class="anime-card">
                <div class="anime-image">葬送的芙莉莲</div>
                <div class="anime-info">
                    <div class="anime-title">葬送的芙莉莲</div>
                    <div class="anime-desc">精灵魔法使芙莉莲在漫长岁月中重新认识人类情感的故事</div>
                    <div class="anime-tags">
                        <span class="tag">奇幻</span>
                        <span class="tag">治愈</span>
                        <span class="tag">2023</span>
                    </div>
                </div>
            </div>
            
            <div class="anime-card">
                <div class="anime-image">咒术回战 第二季</div>
                <div class="anime-info">
                    <div class="anime-title">咒术回战 第二季</div>
                    <div class="anime-desc">怀玉・玉折篇与涩谷事变篇，五条悟的过去与大规模咒灵袭击</div>
                    <div class="anime-tags">
                        <span class="tag">战斗</span>
                        <span class="tag">黑暗奇幻</span>
                        <span class="tag">2023</span>
                    </div>
                </div>
            </div>
            
            <div class="anime-card">
                <div class="anime-image">药屋少女的呢喃</div>
                <div class="anime-info">
                    <div class="anime-title">药屋少女的呢喃</div>
                    <div class="anime-desc">精通药理的少女猫猫在古代宫廷中解决各种疑难事件</div>
                    <div class="anime-tags">
                        <span class="tag">历史</span>
                        <span class="tag">推理</span>
                        <span class="tag">2023</span>
                    </div>
                </div>
            </div>
            
            <div class="anime-card">
                <div class="anime-image">我推的孩子</div>
                <div class="anime-info">
                    <div class="anime-title">我推的孩子</div>
                    <div class="anime-desc">医生转生成偶像的儿子，在演艺圈寻找母亲死亡真相</div>
                    <div class="anime-tags">
                        <span class="tag">偶像</span>
                        <span class="tag">悬疑</span>
                        <span class="tag">2023</span>
                    </div>
                </div>
            </div>
            
            <div class="anime-card">
                <div class="anime-image">钢之炼金术师FA</div>
                <div class="anime-info">
                    <div class="anime-title">钢之炼金术师FA</div>
                    <div class="anime-desc">爱德华和阿尔冯斯兄弟为找回身体而寻找贤者之石的冒险</div>
                    <div class="anime-tags">
                        <span class="tag">冒险</span>
                        <span class="tag">热血</span>
                        <span class="tag">2009</span>
                    </div>
                </div>
            </div>
            
            <div class="anime-card">
                <div class="anime-image">命运石之门</div>
                <div class="anime-info">
                    <div class="anime-title">命运石之门</div>
                    <div class="anime-desc">年轻人发明时间机器，引发世界线变动和悲剧</div>
                    <div class="anime-tags">
                        <span class="tag">科幻</span>
                        <span class="tag">悬疑</span>
                        <span class="tag">2011</span>
                    </div>
                </div>
            </div>
        </div>
        
        <footer>
            <p>个人动漫收藏推荐 • 仅用于分享交流</p>
        </footer>
    </div>
</body>
</html>
