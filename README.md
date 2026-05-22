<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>花卉百科 - 介绍·品种·种植地</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "华文仿宋", SimSun, serif;
        }

        body {
            background: linear-gradient(120deg, #fef6f9, #f0f8f5);
            color: #2c2c2c;
            line-height: 1.8;
        }

        header {
            background: linear-gradient(135deg, #8eacbb, #71a98d);
            color: #fff;
            text-align: center;
            padding: 3rem 1rem;
            box-shadow: 0 4px 20px rgba(0,0,0,0.15);
        }

        header h1 {
            font-size: 2.4rem;
            letter-spacing: 4px;
            margin-bottom: 0.8rem;
            text-shadow: 1px 1px 3px rgba(0,0,0,0.2);
        }

        header p {
            font-size: 1.2rem;
            opacity: 0.92;
            letter-spacing: 2px;
        }

        .container {
            max-width: 1180px;
            margin: 3rem auto;
            padding: 0 1.5rem;
        }

        .card {
            background: rgba(255,255,255,0.92);
            border-radius: 16px;
            padding: 2.5rem;
            margin-bottom: 2.5rem;
            box-shadow: 0 6px 24px rgba(110,160,130,0.18);
            border: 1px solid rgba(180,210,195,0.3);
            transition: all 0.4s ease;
        }

        .card:hover {
            transform: translateY(-8px);
            box-shadow: 0 10px 32px rgba(110,160,130,0.25);
        }

        .card h2 {
            color: #538d6c;
            font-size: 1.8rem;
            margin-bottom: 1.5rem;
            padding-bottom: 0.8rem;
            border-bottom: 2px solid #b4d8c4;
            display: inline-block;
            letter-spacing: 2px;
        }

        .intro-content {
            font-size: 1.1rem;
            color: #444;
            text-indent: 2em;
        }

        .variety-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 2rem;
            margin-top: 1.2rem;
        }

        .variety-item {
            background: linear-gradient(to right, #f7fbf9, #f0f7f3);
            border-left: 5px solid #71a98d;
            padding: 1.3rem;
            border-radius: 10px;
        }

        .variety-item h3 {
            color: #3d6b52;
            font-size: 1.25rem;
            margin-bottom: 0.8rem;
            letter-spacing: 1px;
            text-align: center;
        }

        .flower-img {
            width: 100%;
            height: 180px;
            object-fit: cover;
            border-radius: 8px;
            margin: 1rem 0;
        }

        .list {
            list-style: none;
            margin-top: 1.2rem;
        }

        .list li {
            padding: 1rem 1.2rem 1rem 2.5rem;
            background: linear-gradient(to right, #f7fbf9, #f0f7f3);
            border-radius: 10px;
            margin-bottom: 1rem;
            position: relative;
            font-size: 1.08rem;
            transition: 0.3s;
        }

        .list li:hover {
            background: #e8f3ed;
        }

        .list li::before {
            content: "🌺";
            position: absolute;
            left: 0.8rem;
            top: 50%;
            transform: translateY(-50%);
            font-size: 1.2rem;
        }

        footer {
            text-align: center;
            padding: 2rem;
            color: #608070;
            background: rgba(255,255,255,0.85);
            margin-top: 2rem;
            font-size: 1.05rem;
            letter-spacing: 1px;
        }
    </style>
</head>
<body>
    <header>
        <h1>花卉百科鉴赏</h1>
        <p>花卉简介 · 品类划分 · 产地分布</p>
    </header>

    <div class="container">
        <div class="card">
            <h2>🌸 花卉介绍</h2>
            <div class="intro-content">
                <p>花卉泛指具备观赏价值的各类草木植物，身姿曼妙、花色纷呈、馨香雅致，既是装点自然景致的瑰宝，也深度融入日常生活。广泛应用于园林造景、居家陈设、花艺创作，同时在食疗、香料、医药等领域都有着重要用途。</p>
                <br>
                <p>花草承载人文情怀，寄托美好寓意，不同品类习性各异、风姿独具，装点着四季风光，丰富着世间百态。</p>
            </div>
        </div>

        <div class="card">
            <h2>🌼 常见花卉品种</h2>
            <div class="variety-grid">
                <div class="variety-item">
                    <h3>草本花卉</h3>
                    <img class="flower-img" src="https://pic.baike.soso.com/ugc/baikepic2/31633/cut-20210312154113-1513567041.jpg" alt="草本花卉">
                    <p>月季、菊花、康乃馨、百合、郁金香、满天星</p>
                </div>
                <div class="variety-item">
                    <h3>木本花卉</h3>
                    <img class="flower-img" src="https://pic.baike.soso.com/ugc/baikepic2/28937/cut-20200519171107-1806497964.jpg" alt="木本花卉">
                    <p>牡丹、玫瑰、山茶、桂花、梅花、杜鹃</p>
                </div>
                <div class="variety-item">
                    <h3>球根花卉</h3>
                    <img class="flower-img" src="https://pic.baike.soso.com/ugc/baikepic2/31634/cut-20210312154312-1346692104.jpg" alt="球根花卉">
                    <p>水仙、朱顶红、大丽花、鸢尾、仙客来</p>
                </div>
                <div class="variety-item">
                    <h3>水生花卉</h3>
                    <img class="flower-img" src="https://pic.baike.soso.com/ugc/baikepic2/29431/cut-20200716160413-1193912784.jpg" alt="水生花卉">
                    <p>荷花、睡莲、菖蒲、再力花、凤眼莲</p>
                </div>
            </div>
        </div>

        <div class="card">
            <h2>🌍 花卉主要种植地</h2>
            <ul class="list">
                <li><strong>云南昆明</strong>：全国核心花卉产区，盛产玫瑰、百合、康乃馨</li>
                <li><strong>广东广州</strong>：华南花卉基地，兰花、菊花、年宵花主产地</li>
                <li><strong>山东菏泽</strong>：牡丹之乡，牡丹种植规模位居全国首位</li>
                <li><strong>福建漳州</strong>：知名水仙产地，水仙培育历史悠久</li>
                <li><strong>江苏苏州</strong>：传统名花产区，芍药、盆景远近闻名</li>
                <li><strong>浙江杭州</strong>：桂花、茶花、荷花经典种植区域</li>
                <li><strong>河南洛阳</strong>：千年牡丹名城，名贵牡丹品种繁多</li>
                <li><strong>海南地区</strong>：热带花卉沃土，盛产三角梅、天堂鸟</li>
            </ul>
        </div>
    </div>

    <footer>
        花卉知识展示网页 &copy; 2026
    </footer>
</body>
</html>
