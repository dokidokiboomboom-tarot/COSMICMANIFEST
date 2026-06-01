<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>COMPUTEX 下午參觀攻略｜非科技人靈感採集版</title>
  <style>
    :root {
      --bg: #fff7ef;
      --card: rgba(255,255,255,0.86);
      --ink: #2c2522;
      --muted: #786b63;
      --orange: #ff8b4a;
      --coral: #ff6f61;
      --peach: #ffd2bc;
      --cream: #fffaf4;
      --line: rgba(44,37,34,.12);
      --green: #6ba983;
      --blue: #668bc4;
      --shadow: 0 18px 45px rgba(91, 54, 33, .12);
    }

    * { box-sizing: border-box; }

    body {
      margin: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", "Noto Sans TC", "PingFang TC", "Microsoft JhengHei", sans-serif;
      color: var(--ink);
      background:
        radial-gradient(circle at 12% 10%, rgba(255,139,74,.24), transparent 32%),
        radial-gradient(circle at 88% 18%, rgba(102,139,196,.22), transparent 30%),
        radial-gradient(circle at 60% 92%, rgba(255,111,97,.18), transparent 38%),
        var(--bg);
      line-height: 1.65;
    }

    .wrap {
      width: min(1040px, 92vw);
      margin: 0 auto;
      padding: 42px 0 60px;
    }

    .hero {
      position: relative;
      overflow: hidden;
      padding: 34px;
      border-radius: 32px;
      background: linear-gradient(135deg, rgba(255,255,255,.92), rgba(255,245,236,.88));
      box-shadow: var(--shadow);
      border: 1px solid rgba(255,255,255,.75);
    }

    .hero::after {
      content: "";
      position: absolute;
      right: -70px;
      top: -70px;
      width: 210px;
      height: 210px;
      border-radius: 50%;
      background: radial-gradient(circle, rgba(255,139,74,.36), transparent 68%);
    }

    .badge {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      padding: 8px 14px;
      border-radius: 999px;
      background: #fff0e6;
      color: #9c4f20;
      font-size: 14px;
      font-weight: 700;
      letter-spacing: .03em;
      margin-bottom: 14px;
    }

    h1 {
      margin: 0;
      font-size: clamp(32px, 6vw, 62px);
      line-height: 1.05;
      letter-spacing: -0.06em;
    }

    .subtitle {
      margin: 18px 0 0;
      max-width: 720px;
      color: var(--muted);
      font-size: 18px;
    }

    .hero-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 14px;
      margin-top: 28px;
    }

    .mini {
      padding: 16px;
      border-radius: 22px;
      background: rgba(255,255,255,.72);
      border: 1px solid var(--line);
    }

    .mini strong {
      display: block;
      margin-bottom: 4px;
      font-size: 15px;
    }

    .mini span {
      color: var(--muted);
      font-size: 14px;
    }

    .section {
      margin-top: 28px;
    }

    .section-title {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 12px;
      margin-bottom: 14px;
    }

    h2 {
      margin: 0;
      font-size: 26px;
      letter-spacing: -0.03em;
    }

    .hint {
      color: var(--muted);
      font-size: 14px;
    }

    .timeline {
      display: grid;
      gap: 14px;
    }

    .slot {
      display: grid;
      grid-template-columns: 150px 1fr;
      gap: 18px;
      padding: 20px;
      border-radius: 28px;
      background: var(--card);
      box-shadow: 0 14px 34px rgba(67, 48, 35, .08);
      border: 1px solid rgba(255,255,255,.74);
    }

    .time {
      font-weight: 900;
      color: var(--coral);
      font-size: 18px;
    }

    .place {
      margin: 0 0 6px;
      font-size: 21px;
      font-weight: 900;
      letter-spacing: -0.02em;
    }

    .why {
      margin: 0;
      color: var(--muted);
    }

    .tags {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
      margin-top: 12px;
    }

    .tag {
      padding: 6px 10px;
      border-radius: 999px;
      background: #fff0e6;
      color: #8c4622;
      font-size: 13px;
      font-weight: 700;
    }

    .grid-2 {
      display: grid;
      grid-template-columns: 1.1fr .9fr;
      gap: 18px;
      margin-top: 18px;
    }

    .card {
      padding: 24px;
      border-radius: 30px;
      background: var(--card);
      border: 1px solid rgba(255,255,255,.75);
      box-shadow: 0 14px 34px rgba(67, 48, 35, .08);
    }

    .card h3 {
      margin: 0 0 12px;
      font-size: 22px;
      letter-spacing: -0.03em;
    }

    .list {
      display: grid;
      gap: 10px;
      padding: 0;
      margin: 0;
      list-style: none;
    }

    .list li {
      display: grid;
      grid-template-columns: 28px 1fr;
      gap: 10px;
      align-items: start;
      color: var(--muted);
    }

    .num {
      width: 28px;
      height: 28px;
      display: grid;
      place-items: center;
      border-radius: 50%;
      background: var(--peach);
      color: #7a3518;
      font-weight: 900;
      font-size: 13px;
      flex: none;
    }

    .focus-box {
      display: grid;
      gap: 12px;
    }

    .focus {
      padding: 16px;
      border-radius: 22px;
      background: var(--cream);
      border: 1px solid var(--line);
    }

    .focus b {
      display: block;
      margin-bottom: 4px;
    }

    .focus p {
      margin: 0;
      color: var(--muted);
      font-size: 14px;
    }

    .avoid {
      background: linear-gradient(135deg, rgba(255,255,255,.9), rgba(255,236,230,.82));
    }

    .quote {
      position: relative;
      padding: 30px;
      border-radius: 32px;
      background: #2c2522;
      color: #fffaf4;
      overflow: hidden;
      box-shadow: var(--shadow);
    }

    .quote::before {
      content: "✦";
      position: absolute;
      right: 24px;
      top: 18px;
      color: rgba(255,255,255,.28);
      font-size: 70px;
    }

    .quote h2 { color: #fff; }
    .quote p { color: rgba(255,255,255,.78); margin: 12px 0 0; }

    .output-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 12px;
    }

    .output {
      padding: 16px;
      border-radius: 22px;
      background: #fff;
      border: 1px solid var(--line);
      font-weight: 800;
    }

    .footer {
      margin-top: 28px;
      text-align: center;
      color: var(--muted);
      font-size: 14px;
    }

    .print-note {
      margin-top: 14px;
      padding: 14px 16px;
      border-radius: 20px;
      background: rgba(255,255,255,.66);
      border: 1px dashed rgba(44,37,34,.2);
      color: var(--muted);
      font-size: 14px;
    }

    @media (max-width: 760px) {
      .wrap { padding-top: 22px; }
      .hero { padding: 24px; border-radius: 26px; }
      .hero-grid, .grid-2, .output-grid { grid-template-columns: 1fr; }
      .slot { grid-template-columns: 1fr; gap: 8px; }
      .time { font-size: 17px; }
      .section-title { align-items: flex-start; flex-direction: column; }
    }

    @media print {
      body { background: #fff7ef; }
      .wrap { width: 94%; padding: 18px 0; }
      .hero, .card, .slot, .quote { box-shadow: none; }
    }
  </style>
</head>
<body>
  <main class="wrap">
    <section class="hero">
      <div class="badge">🛰️ COMPUTEX 下午參觀攻略</div>
      <h1>非科技人也能逛出靈感的<br />南港採集路線</h1>
      <p class="subtitle">不要把自己丟進規格海裡滅頂。妳明天的任務不是看懂每顆晶片，而是看懂：AI 怎麼被包裝、科技怎麼被賣、企業怎麼把技術講成人聽得懂的商業價值。</p>

      <div class="hero-grid">
        <div class="mini"><strong>主路線</strong><span>南港二館優先，InnoVEX 展區為核心，Pi Stage 當可選確認點</span></div>
        <div class="mini"><strong>逛展身份</strong><span>行銷企劃 × AI 應用 × 商業靈感獵人</span></div>
        <div class="mini"><strong>帶回成果</strong><span>社群題材、白皮書觀點、活動包裝靈感</span></div>
      </div>
    </section>

    <section class="section">
      <div class="section-title">
        <h2>明天下午路線表</h2>
        <div class="hint">建議從 14:00 開始，節奏剛好不崩壞</div>
      </div>

      <div class="timeline">
        <article class="slot">
          <div class="time">14:00－14:20</div>
          <div>
            <h3 class="place">4F S區｜先確認 Pi Stage 是否可入場</h3>
            <p class="why">Pi Stage 的 TOP TIER Pitch & Panel 官方議程有 Registration & Check-in，且內容偏英文。到現場先看是否開放旁聽；如果需要報名、座位滿或英文聽起來太硬，就不要硬卡，直接把它當地標，轉去逛 InnoVEX 攤位。</p>
            <div class="tags"><span class="tag">可選</span><span class="tag">先確認</span><span class="tag">不硬聽</span></div>
          </div>
        </article>

        <article class="slot">
          <div class="time">14:20－15:40</div>
          <div>
            <h3 class="place">InnoVEX 展區｜鎖定 AI、MarTech、電商、新創</h3>
            <p class="why">這才是明天下午的主菜。妳可以找 AI 工具、社群科技、電商應用、企業軟體，觀察哪些產品能變成內容、活動、商機或副業選品靈感。看不懂技術沒關係，妳看它怎麼說人話。</p>
            <div class="tags"><span class="tag">MarTech</span><span class="tag">e-Commerce</span><span class="tag">Enterprise Software</span><span class="tag">AI應用</span></div>
          </div>
        </article>

        <article class="slot">
          <div class="time">15:40－16:25</div>
          <div>
            <h3 class="place">智慧商業服務解決方案區</h3>
            <p class="why">看 POS、智慧零售、會員經營、無人服務、商業流程工具。重點不是機器多厲害，而是它如何讓中小企業省人、省時間、提升轉換。</p>
            <div class="tags"><span class="tag">智慧零售</span><span class="tag">會員經營</span><span class="tag">中小企業數位轉型</span></div>
          </div>
        </article>

        <article class="slot">
          <div class="time">16:25－17:10</div>
          <div>
            <h3 class="place">大品牌 AI 展區｜只看品牌怎麼說 AI</h3>
            <p class="why">不要硬背規格。妳要看主視覺、標語、Demo 動線、觀眾停留點。大品牌怎麼把 AI 講成效率、創作、商務、安全或生活體驗，這才是行銷人的寶藏。</p>
            <div class="tags"><span class="tag">品牌敘事</span><span class="tag">主視覺</span><span class="tag">展場動線</span><span class="tag">AI賣點</span></div>
          </div>
        </article>

        <article class="slot">
          <div class="time">17:10－17:30</div>
          <div>
            <h3 class="place">收尾整理｜拍 3 張、記 3 句、想 1 篇</h3>
            <p class="why">拍 3 張展場視覺，記 3 句好文案，想 1 個可以回去發的社群觀察。不要空手離開，妳是去採蜜，不是去健走。</p>
            <div class="tags"><span class="tag">社群素材</span><span class="tag">白皮書觀點</span><span class="tag">主管週報</span></div>
          </div>
        </article>
      </div>
    </section>

    <section class="section grid-2">
      <div class="card">
        <h3>妳最該看的 4 種攤位</h3>
        <div class="focus-box">
          <div class="focus"><b>1. MarTech / Social Networking</b><p>看 AI 怎麼做內容、導流、社群、會員經營，這會直接變成妳的社群企劃素材。</p></div>
          <div class="focus"><b>2. e-Commerce / Consumer Tech</b><p>看哪些商品適合快電商、生活選品、社群導購，不只看產品，也看它怎麼讓人想買。</p></div>
          <div class="focus"><b>3. Enterprise Software</b><p>看它如何把功能翻譯成省時間、降成本、提高轉換、管理變簡單。</p></div>
          <div class="focus"><b>4. AI 新創</b><p>看 AI 如何從工具變成解方，特別適合轉成 B2B 貼文與活動主題。舞台活動可旁聽就聽，不行就逛攤位，攤位反而更容易問問題。</p></div>
        </div>
      </div>

      <div class="card avoid">
        <h3>先不用深逛的區</h3>
        <ul class="list">
          <li><span class="num">×</span><span><b>半導體零組件</b><br />除非妳要寫供應鏈，不然容易看得很硬，靈魂會開始轉圈圈。</span></li>
          <li><span class="num">×</span><span><b>電源、散熱、模組規格</b><br />可以快速拍大廠氣勢照，但不必在規格牌前面跟自己硬拚。</span></li>
          <li><span class="num">×</span><span><b>跨館奔波</b><br />下午時間有限，南港二館先吃乾淨，比到處跑更有效。</span></li>
        </ul>
      </div>
    </section>

    <section class="section grid-2">
      <div class="card">
        <h3>逛展時問自己的 5 個問題</h3>
        <ul class="list">
          <li><span class="num">1</span><span>這個產品解決的是誰的痛點？</span></li>
          <li><span class="num">2</span><span>它有沒有一句話讓非科技人聽懂？</span></li>
          <li><span class="num">3</span><span>它能不能被包裝成社群貼文、白皮書案例或活動主題？</span></li>
          <li><span class="num">4</span><span>它適合 B2B 企業、中小企業，還是個人創作者？</span></li>
          <li><span class="num">5</span><span>如果我要幫它寫廣告，第一句話會怎麼寫？</span></li>
        </ul>
      </div>

      <div class="quote">
        <h2>明天的核心心法</h2>
        <p>別人看晶片，妳看趨勢。別人看規格，妳看話術。別人拿型錄，妳要拿回一整包社群靈感。</p>
      </div>
    </section>

    <section class="section">
      <div class="section-title">
        <h2>回來可以產出的內容題目</h2>
        <div class="hint">直接當 Threads、FB、主管週報靈感</div>
      </div>
      <div class="output-grid">
        <div class="output">非科技人逛 COMPUTEX：我看到的不是晶片，是未來商業的語言</div>
        <div class="output">AI 展場逛一圈，我發現會賣的科技公司都在講同一件事</div>
        <div class="output">中小企業不用先懂 AI，先懂自己的流程卡在哪裡</div>
        <div class="output">從新創簡報看懂：一個好產品，必須先會說人話</div>
        <div class="output">科技展不是只有工程師能逛，行銷人其實更該去</div>
        <div class="output">把 AI 從規格表翻譯成買主聽得懂的價值</div>
      </div>
    </section>

    <div class="print-note">📌 小提醒：手機打開這頁照著走就好。現場不用貪多，妳的目標是採集「可以被轉成內容與商業洞察」的東西。</div>
    <div class="footer">COMPUTEX 下午參觀攻略｜奶茶專屬商業靈感採集版 ✨</div>
  </main>
</body>
</html>
