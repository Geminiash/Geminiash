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
            min-height: 100vh;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        header {
            text-align: center;
            padding: 40px 0;
            margin-bottom: 40px;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        h1 {
            font-size: 3rem;
            margin-bottom: 10px;
            background: linear-gradient(90deg, #ff6b6b, #ffa36c, #ffde7d, #a3de83, #6a98f0);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-shadow: 0 0 20px rgba(255, 107, 107, 0.3);
        }
        
        h2 {
            font-size: 1.5rem;
            color: #a3de83;
            margin: 30px 0 15px;
            padding-bottom: 10px;
            border-bottom: 1px solid rgba(163, 222, 131, 0.3);
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
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .anime-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.4);
        }
        
        .anime-image {
            width: 100%;
            height: 320px;
            object-fit: cover;
            display: block;
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
            display: -webkit-box;
            -webkit-line-clamp: 3;
            -webkit-box-orient: vertical;
            overflow: hidden;
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
        
        .tag.genre {
            background: rgba(255, 107, 107, 0.2);
            color: #ff6b6b;
        }
        
        .tag.year {
            background: rgba(163, 222, 131, 0.2);
            color: #a3de83;
        }
        
        .section {
            margin-bottom: 60px;
            opacity: 0;
            transform: translateY(30px);
            animation: fadeInUp 0.8s ease forwards;
        }
        
        .section:nth-child(2) {
            animation-delay: 0.2s;
        }
        
        .section:nth-child(3) {
            animation-delay: 0.4s;
        }
        
        .section:nth-child(4) {
            animation-delay: 0.6s;
        }
        
        @keyframes fadeInUp {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        footer {
            text-align: center;
            padding: 30px 0;
            margin-top: 50px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            color: #888;
            font-size: 0.9rem;
        }
        
        @media (max-width: 768px) {
            .anime-grid {
                grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
                gap: 20px;
            }
            
            h1 {
                font-size: 2.2rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>动漫推荐收藏</h1>
            <p>精心挑选的优质动漫作品</p>
        </header>
        
        <section class="section">
            <h2>🎌 热门新番推荐</h2>
            <div class="anime-grid">
                <div class="anime-card">
                    <img src="https://via.placeholder.com/300x400/2d3748/FFFFFF?text=葬送的芙莉莲" alt="葬送的芙莉莲" class="anime-image">
                    <div class="anime-info">
                        <div class="anime-title">葬送的芙莉莲</div>
                        <div class="anime-desc">讲述了精灵魔法使芙莉莲与勇者一行人打倒魔王后，在漫长岁月中重新认识人类情感的故事。</div>
                        <div class="anime-tags">
                            <span class="tag genre">奇幻</span>
                            <span class="tag genre">治愈</span>
                            <span class="tag year">2023</span>
                        </div>
                    </div>
                </div>
                
                <div class="anime-card">
                    <img src="https://via.placeholder.com/300x400/2d3748/FFFFFF?text=咒术回战+第二季" alt="咒术回战 第二季" class="anime-image">
                    <div class="anime-info">
                        <div class="anime-title">咒术回战 第二季</div>
                        <div class="anime-desc">怀玉・玉折篇与涩谷事变篇，讲述五条悟的过去以及涩谷的大规模咒灵袭击事件。</div>
                        <div class="anime-tags">
                            <span class="tag genre">战斗</span>
                            <span class="tag genre">黑暗奇幻</span>
                            <span class="tag year">2023</span>
                        </div>
                    </div>
                </div>
                
                <div class="anime-card">
                    <img src="https://via.placeholder.com/300x400/2d3748/FFFFFF?text=药屋少女的呢喃" alt="药屋少女的呢喃" class="anime-image">
                    <div class="anime-info">
                        <div class="anime-title">药屋少女的呢喃</div>
                        <div class="anime-desc">在古代宫廷中，一位精通药理的少女猫猫解决各种疑难事件的故事。</div>
                        <div class="anime-tags">
                            <span class="tag genre">历史</span>
                            <span class="tag genre">推理</span>
                            <span class="tag year">2023</span>
                        </div>
                    </div>
                </div>
                
                <div class="anime-card">
                    <img src="https://via.placeholder.com/300x400/2d3748/FFFFFF?text=我推的孩子" alt="我推的孩子" class="anime-image">
                    <div class="anime-info">
                        <div class="anime-title">我推的孩子</div>
                        <div class="anime-desc">妇产科医生转生成自己推的偶像的儿子，在演艺圈中寻找母亲死亡真相的故事。</div>
                        <div class="anime-tags">
                            <span class="tag genre">偶像</span>
                            <span class="tag genre">悬疑</span>
                            <span class="tag year">2023</span>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
        <section class="section">
            <h2>🏆 经典必看神作</h2>
            <div class="anime-grid">
                <div class="anime-card">
                    <img src="https://via.placeholder.com/300x400/2d3748/FFFFFF?text=钢之炼金术师FA" alt="钢之炼金术师FA" class="anime-image">
                    <div class="anime-info">
                        <div class="anime-title">钢之炼金术师FA</div>
                        <div class="anime-desc">爱德华和阿尔冯斯兄弟为找回身体而寻找贤者之石的冒险故事，零差评神作。</div>
                        <div class="anime-tags">
                            <span class="tag genre">冒险</span>
                            <span class="tag genre">热血</span>
                            <span class="tag year">2009</span>
                        </div>
                    </div>
                </div>
                
                <div class="anime-card">
                    <img src="https://via.placeholder.com/300x400/2d3748/FFFFFF?text=命运石之门" alt="命运石之门" class="anime-image">
                    <div class="anime-info">
                        <div class="anime-title">命运石之门</div>
                        <div class="anime-desc">一群年轻人偶然发明了时间机器，却引发了一系列世界线变动和悲剧。</div>
                        <div class="anime-tags">
                            <span class="tag genre">科幻</span>
                            <span class="tag genre">悬疑</span>
                            <span class="tag year">2011</span>
                        </div>
                    </div>
                </div>
                
                <div class="anime-card">
                    <img src="https://via.placeholder.com/300x400/2d3748/FFFFFF?text=进击的巨人" alt="进击的巨人" class="anime-image">
                    <div class="anime-info">
                        <div class="anime-title">进击的巨人</div>
                        <div class="anime-desc">人类生活在被巨人包围的城墙内，少年艾伦立志消灭所有巨人的史诗故事。</div>
                        <div class="anime-tags">
                            <span class="tag genre">黑暗奇幻</span>
                            <span class="tag genre">战斗</span>
                            <span class="tag year">2013</span>
                        </div>
                    </div>
                </div>
                
                <div class="anime-card">
                    <img src="https://via.placeholder.com/300x400/2d3748/FFFFFF?text=CLANNAD" alt="CLANNAD" class="anime-image">
                    <div class="anime-info">
                        <div class="anime-title">CLANNAD</div>
                        <div class="anime-desc">不良少年冈崎朋也在小镇上遇到各种女孩，经历亲情、友情和爱情的故事。</div>
                        <div class="anime-tags">
                            <span class="tag genre">治愈</span>
                            <span class="tag genre">恋爱</span>
                            <span class="tag year">2007</span>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
        <section class="section">
            <h2>💎 冷门佳作推荐</h2>
            <div class="anime-grid">
                <div class="anime-card">
                    <img src="https://via.placeholder.com/300x400/2d3748/FFFFFF?text=奇诺之旅" alt="奇诺之旅" class="anime-image">
                    <div class="anime-info">
                        <div class="anime-title">奇诺之旅</div>
                        <div class="anime-desc">少女奇诺与会说话的摩托车汉密斯周游列国，见证各种奇特国度的故事。</div>
                        <div class="anime-tags">
                            <span class="tag genre">哲理</span>
                            <span class="tag genre">旅行</span>
                            <span class="tag year">2003</span>
                        </div>
                    </div>
                </div>
                
                <div class="anime-card">
                    <img src="https://via.placeholder.com/300x400/2d3748/FFFFFF?text=昭和元禄落语心中" alt="昭和元禄落语心中" class="anime-image">
                    <div class="anime-info">
                        <div class="anime-title">昭和元禄落语心中</div>
                        <div class="anime-desc">围绕落语艺术家们的爱恨情仇，展现日本传统艺术落语的魅力。</div>
                        <div class="anime-tags">
                            <span class="tag genre">艺术</span>
                            <span class="tag genre">历史</span>
                            <span class="tag year">2016</span>
                        </div>
                    </div>
                </div>
                
                <div class="anime-card">
                    <img src="https://via.placeholder.com/300x400/2d3748/FFFFFF?text=三月的狮子" alt="三月的狮子" class="anime-image">
                    <div class="anime-info">
                        <div class="anime-title">三月的狮子</div>
                        <div class="anime-desc">职业将棋棋手桐山零在孤独中成长，与三姐妹相遇后逐渐打开心扉的故事。</div>
                        <div class="anime-tags">
                            <span class="tag genre">将棋</span>
                            <span class="tag genre">治愈</span>
                            <span class="tag year">2016</span>
                        </div>
                    </div>
                </div>
                
                <div class="anime-card">
                    <img src="https://via.placeholder.com/300x400/2d3748/FFFFFF?text=编舟记" alt="编舟记" class="anime-image">
                    <div class="anime-info">
                        <div class="anime-title">编舟记</div>
                        <div class="anime-desc">一群人为编纂一本名为《大渡海》的辞典而付出毕生心血的故事。</div>
                        <div class="anime-tags">
                            <span class="tag genre">职场</span>
                            <span class="tag genre">文学</span>
                            <span class="tag year">2016</span>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
        <footer>
            <p>个人动漫收藏推荐 • 仅用于分享交流</p>
        </footer>
    </div>
</body>
</html>
