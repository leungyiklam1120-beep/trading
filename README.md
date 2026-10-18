<!DOCTYPE html>
<html lang="zh-HK">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>XX Trading｜交易公司</title>
<style>
  * { margin:0; padding:0; box-sizing:border-box; }
  html { scroll-behavior:smooth; }
  body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", "PingFang HK", "Microsoft JhengHei", sans-serif;
    color:#111; background:#fff; line-height:1.7;
  }
  a { color:inherit; text-decoration:none; }
  .container { width:min(1120px, 90%); margin:0 auto; }

  /* Nav */
  header {
    position:sticky; top:0; z-index:100;
    background:rgba(255,255,255,.92);
    backdrop-filter:blur(10px);
    border-bottom:1px solid #eee;
  }
  nav {
    display:flex; justify-content:space-between; align-items:center;
    height:72px;
  }
  .logo { font-weight:700; letter-spacing:.08em; font-size:18px; }
  .logo span { color:#b08d57; }
  .nav-links { display:flex; gap:28px; font-size:14px; color:#555; }
  .nav-links a:hover { color:#111; }

  /* Hero */
  .hero {
    padding:110px 0 90px;
    border-bottom:1px solid #eee;
  }
  .hero small {
    display:inline-block; color:#b08d57; font-size:13px;
    letter-spacing:.18em; text-transform:uppercase; margin-bottom:20px;
  }
  .hero h1 {
    font-size:clamp(36px, 6vw, 64px);
    line-height:1.1; letter-spacing:-.03em; font-weight:700;
    max-width:800px; margin-bottom:24px;
  }
  .hero p {
    color:#666; font-size:18px; max-width:560px; margin-bottom:36px;
  }
  .btn {
    display:inline-block; padding:14px 28px;
    background:#111; color:#fff; font-size:14px; letter-spacing:.05em;
    border:1px solid #111; transition:.25s;
  }
  .btn:hover { background:#b08d57; border-color:#b08d57; }
  .btn.ghost { background:transparent; color:#111; margin-left:10px; }
  .btn.ghost:hover { background:#111; color:#fff; border-color:#111; }

  /* Sections */
  section { padding:90px 0; border-bottom:1px solid #eee; }
  .section-title small {
    color:#b08d57; font-size:12px; letter-spacing:.18em;
    text-transform:uppercase;
  }
  .section-title h2 {
    font-size:clamp(26px, 4vw, 40px);
    margin:10px 0 40px; letter-spacing:-.02em;
  }

  /* Services */
  .grid { display:grid; grid-template-columns:repeat(3,1fr); gap:24px; }
  .card {
    padding:32px; border:1px solid #e8e8e8;
    transition:.25s; background:#fff;
  }
  .card:hover { border-color:#b08d57; transform:translateY(-4px); }
  .card h3 { font-size:18px; margin-bottom:12px; }
  .card p { color:#666; font-size:14px; }

  /* About */
  .about-grid { display:grid; grid-template-columns:1fr 1fr; gap:60px; align-items:start; }
  .about-grid p { color:#555; margin-bottom:16px; }
  .stats { display:grid; grid-template-columns:1fr 1fr; gap:24px; }
  .stat { border-top:2px solid #111; padding-top:16px; }
  .stat strong { display:block; font-size:32px; letter-spacing:-.02em; }
  .stat span { color:#777; font-size:13px; }

  /* Contact */
  .contact-grid { display:grid; grid-template-columns:1fr 1fr; gap:60px; }
  .contact-info p { color:#555; margin-bottom:12px; }
  form { display:grid; gap:16px; }
  input, textarea {
    width:100%; padding:14px; border:1px solid #ddd;
    font:inherit; background:#fafafa; outline:none;
  }
  input:focus, textarea:focus { border-color:#111; background:#fff; }
  textarea { min-height:130px; resize:vertical; }
  button {
    padding:14px; background:#111; color:#fff; border:0;
    font:inherit; cursor:pointer; letter-spacing:.05em;
  }
  button:hover { background:#b08d57; }

  /* Footer */
  footer { padding:36px 0; color:#888; font-size:13px; }
  .footer-inner { display:flex; justify-content:space-between; gap:20px; flex-wrap:wrap; }

  /* Mobile */
  @media (max-width: 800px) {
    .nav-links { display:none; }
    .grid, .about-grid, .contact-grid { grid-template-columns:1fr; }
    .hero { padding:80px 0 60px; }
    section { padding:70px 0; }
    .btn.ghost { margin-left:0; margin-top:10px; }
  }
</style>
</head>
<body>

<header>
  <nav class="container">
    <div class="logo">XX<span>TRADING</span></div>
    <div class="nav-links">
      <a href="#services">服務</a>
      <a href="#about">關於</a>
      <a href="#contact">聯絡</a>
    </div>
  </nav>
</header>

<main>
  <section class="hero">
    <div class="container">
      <small>Global Trading Solutions</small>
      <h1>簡約、可靠、專業嘅交易夥伴。</h1>
      <p>專注商品與市場交易，提供採購、銷售、物流及供應鏈支援，以清晰流程同穩健執行力服務客戶。</p>
      <a class="btn" href="#contact">聯絡我們</a>
      <a class="btn ghost" href="#services">了解服務</a>
    </div>
  </section>

  <section id="services">
    <div class="container">
      <div class="section-title">
        <small>Services</small>
        <h2>我哋提供嘅服務</h2>
      </div>
      <div class="grid">
        <div class="card">
          <h3>商品採購</h3>
          <p>按客戶需求搜尋供應商、議價、樣品確認及採購執行，降低採購風險。</p>
        </div>
        <div class="card">
          <h3>銷售與分銷</h3>
          <p>協助產品進入目標市場，建立分銷渠道，處理報價、訂單及客戶跟進。</p>
        </div>
        <div class="card">
          <h3>物流與供應鏈</h3>
          <p>協調倉儲、運輸、報關及交付安排，提升整體供應鏈效率。</p>
        </div>
      </div>
    </div>
  </section>

  <section id="about">
    <div class="container">
      <div class="section-title">
        <small>About Us</small>
        <h2>關於我們</h2>
      </div>
      <div class="about-grid">
        <div>
          <p>XX Trading 係一間專注國際貿易同商品交易嘅公司，以簡潔、透明同高效為原則，協助客戶處理由採購到交付嘅每個環節。</p>
          <p>我們重視長期合作關係，透過清晰溝通、可靠供應商網絡同嚴謹執行，為客戶創造穩定價值。</p>
        </div>
        <div class="stats">
          <div class="stat"><strong>10+</strong><span>年行業經驗</span></div>
          <div class="stat"><strong>20+</strong><span>合作市場</span></div>
          <div class="stat"><strong>500+</strong><span>完成訂單</span></div>
          <div class="stat"><strong>98%</strong><span>客戶滿意度</span></div>
        </div>
      </div>
    </div>
  </section>

  <section id="contact">
    <div class="container">
      <div class="section-title">
        <small>Contact</small>
        <h2>聯絡我們</h2>
      </div>
      <div class="contact-grid">
        <div class="contact-info">
          <p><strong>地址：</strong>香港中環示例街 1 號 10 樓</p>
          <p><strong>電話：</strong>+852 1234 5678</p>
          <p><strong>電郵：</strong>hello@example.com</p>
          <p><strong>營業時間：</strong>星期一至五 09:00–18:00</p>
        </div>
        <form onsubmit="event.preventDefault(); alert('多謝查詢，我們會盡快聯絡你。'); this.reset();">
          <input type="text" placeholder="姓名" required>
          <input type="email" placeholder="電郵" required>
          <textarea placeholder="查詢內容" required></textarea>
          <button type="submit">送出查詢</button>
        </form>
      </div>
    </div>
  </section>
</main>

<footer>
  <div class="container footer-inner">
    <div>© 2026 XX Trading. All rights reserved.</div>
    <div>本網站資料僅供一般介紹，不構成任何投資建議。</div>
  </div>
</footer>

</body>
</html>