# jinghe-medical
Jinghe Medical Website
<!DOCTYPE html>
<html lang="zh">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>静和医疗 | Jinghe Medical</title>
  <style>
    body {
      margin: 0;
      font-family: "Helvetica Neue", sans-serif;
      background-color: #fefefe;
      color: #333;
    }
    header {
      background-color: #fff;
      border-bottom: 1px solid #eee;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    nav a {
      margin: 0 1rem;
      text-decoration: none;
      color: #666;
      font-weight: 500;
    }
    nav a:hover {
      color: #000;
    }
    .hero {
      text-align: center;
      padding: 6rem 2rem;
      background: linear-gradient(to right, #fbe8f0, #e6f0ff);
    }
    .hero h1 {
      font-size: 3rem;
      margin-bottom: 1rem;
    }
    .hero p {
      font-size: 1.2rem;
      color: #666;
    }
    .section {
      padding: 4rem 2rem;
      max-width: 1000px;
      margin: 0 auto;
    }
    footer {
      text-align: center;
      padding: 2rem;
      background-color: #fafafa;
      font-size: 0.9rem;
      color: #999;
    }
    .lang-switch {
      font-size: 0.9rem;
      cursor: pointer;
      color: #666;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
      margin-top: 2rem;
    }
    .gallery img {
      width: 100%;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
      max-width: 600px;
      margin-top: 2rem;
    }
    form input, form textarea, form button {
      padding: 0.8rem;
      font-size: 1rem;
      border: 1px solid #ccc;
      border-radius: 8px;
    }
    form button {
      background-color: #e6a1c4;
      color: white;
      border: none;
      cursor: pointer;
    }
    form button:hover {
      background-color: #d58bb2;
    }
    .team {
      display: flex;
      gap: 2rem;
      flex-wrap: wrap;
      justify-content: center;
      margin-top: 2rem;
    }
    .team-member {
      text-align: center;
      max-width: 200px;
    }
    .team-member img {
      width: 100%;
      border-radius: 50%;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    .team-member h4 {
      margin-top: 0.5rem;
      margin-bottom: 0.2rem;
    }
    .team-member p {
      font-size: 0.9rem;
      color: #666;
    }
  </style>
</head>
<body>
  <header>
    <div><strong>静和医疗</strong> | Jinghe Medical</div>
    <nav>
      <a href="#about">关于我们</a>
      <a href="#services">服务项目</a>
      <a href="#gallery">案例展示</a>
      <a href="#team">专家团队</a>
      <a href="#contact">联系我们</a>
      <span class="lang-switch">EN / 中文</span>
    </nav>
  </header>

  <div class="hero">
    <h1>优雅之美，从静和开始</h1>
    <p>专业整形外科医疗，为高端女性提供私密、安全与卓越的美学服务</p>
  </div>

  <section class="section" id="about">
    <h2>关于我们</h2>
    <p>
      静和医疗专注于整形外科及非手术美学医疗，致力于将“自然、优雅、安全”作为服务理念，
      为现代女性提供高质量、私密且可信赖的医美体验。
    </p>
  </section>

  <section class="section" id="services">
    <h2>服务项目</h2>
    <ul>
      <li>面部精雕与年轻化手术</li>
      <li>眼部整形与修复</li>
      <li>鼻整形与综合改善</li>
      <li>胸部整形与提升</li>
      <li>身体塑形手术</li>
      <li>注射微整与激光项目</li>
    </ul>
  </section>

  <section class="section" id="gallery">
    <h2>案例展示</h2>
    <div class="gallery">
      <img src="https://via.placeholder.com/300x200?text=Before+%26+After+1" alt="案例1">
      <img src="https://via.placeholder.com/300x200?text=Before+%26+After+2" alt="案例2">
      <img src="https://via.placeholder.com/300x200?text=Facial+Sculpting" alt="面部塑形">
      <img src="https://via.placeholder.com/300x200?text=Eye+Surgery" alt="眼部整形">
    </div>
  </section>

  <section class="section" id="team">
    <h2>专家团队</h2>
    <div class="team">
      <div class="team-member">
        <img src="https://via.placeholder.com/150" alt="Dr. Chen">
        <h4>陈医生</h4>
        <p>首席整形外科专家，20年经验</p>
      </div>
      <div class="team-member">
        <img src="https://via.placeholder.com/150" alt="Dr. Li">
        <h4>李医生</h4>
        <p>面部与激光美容专家</p>
      </div>
      <div class="team-member">
        <img src="https://via.placeholder.com/150" alt="Dr. Wang">
        <h4>王医生</h4>
        <p>胸部整形与综合美体专家</p>
      </div>
    </div>
  </section>

  <section class="section" id="contact">
    <h2>联系我们</h2>
    <p>
      地址：上海市静安区幸福路 88 号 · Jinghe Medical, Jingan District, Shanghai<br>
      电话：+86 21 8888 8888<br>
      邮箱：info@jinghemed.com
    </p>

    <form action="https://formspree.io/f/your-form-id" method="POST">
      <input type="text" name="name" placeholder="您的姓名" required>
      <input type="email" name="email" placeholder="您的邮箱" required>
      <textarea name="message" rows="5" placeholder="请留下您的需求或问题..." required></textarea>
      <button type="submit">提交信息</button>
    </form>
  </section>

  <footer>
    &copy; 2025 静和医疗 Jinghe Medical. All rights reserved.
  </footer>
</body>
</html>
