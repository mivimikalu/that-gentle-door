<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>That Gentle Door | Finding Peace After Pet Loss | Mivimika Lu</title>

<meta name="description" content="A compassionate guide for anyone navigating pet loss and grief. That Gentle Door by Mivimika Lu — featured on the APLB Recommended Reading List.">
<meta name="keywords" content="pet loss book, pet grief, pet bereavement, losing a pet, dog loss, cat loss, pet death grief, pet loss support, rainbow bridge, euthanasia guilt, pet loss guide, grief after pet death">

<script type="application/ld+json">
{"@context":"https://schema.org","@type":"Book","name":"That Gentle Door: Understanding Pet Loss, Love, and Life After Goodbye","author":{"@type":"Person","name":"Mivimika Lu"},"description":"A compassionate guide for anyone navigating pet loss and grief.","genre":["Self-help","Pet Loss","Grief"],"url":"https://www.amazon.com/That-Gentle-Door-Understanding-Goodbye/dp/B0GJNFJV7S"}
</script>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;1,300;1,400&family=Jost:wght@300;400;500&display=swap" rel="stylesheet">

<style>
/* 核心样式变量 */
:root {
  --cream: #f7f3ec;
  --warm-white: #fdfaf5;
  --sand: #e6dfd1; /* 我们讨论的沙色 */
  --gold: #c9a96e;
  --text: #2a2520;
  --mid: #6b5f52;
  --border: rgba(181,172,138,0.2);
}

* { margin:0; padding:0; box-sizing:border-box; }
html { scroll-behavior:smooth; }

body {
  background: var(--cream);
  color: var(--text);
  font-family: 'Jost', sans-serif;
  font-weight: 300;
  line-height: 1.7;
}

/* 1. 导航栏：初始透明，滚动变磨砂白 */
nav {
  position: fixed; top:0; left:0; right:0; z-index:1000;
  padding: 25px 6%;
  display: flex; justify-content: space-between; align-items: center;
  transition: all 0.5s ease;
  background: transparent;
}
nav.scrolled {
  background: rgba(255, 255, 255, 0.75);
  backdrop-filter: blur(15px); /* 磨砂效果 */
  padding: 15px 6%;
  border-bottom: 1px solid var(--border);
}
.nav-logo {
  font-family: 'Cormorant Garamond', serif;
  font-size: 1.2rem; font-style: italic; font-weight: 400;
  color: #fff; text-decoration: none; transition: color 0.4s;
}
nav.scrolled .nav-logo { color: var(--text); }
.nav-links { display: flex; gap: 30px; list-style: none; }
.nav-links a {
  font-size: 0.7rem; letter-spacing: 0.2em; text-transform: uppercase;
  color: rgba(255,255,255,0.9); text-decoration: none; transition: 0.3s;
}
nav.scrolled .nav-links a { color: var(--mid); }
.nav-links a:hover { color: var(--gold) !important; }

/* 2. 英雄区：全屏沉浸大图 */
.hero {
  position: relative; height: 100vh;
  display: flex; align-items: center; justify-content: center;
  text-align: center; color: #fff; overflow: hidden;
}
.hero-bg {
  position: absolute; inset:0; z-index: -1;
  background: url('hero.jpg') center/cover no-repeat; /* 替换成你最有质感的那张图 */
}
.hero-bg::after {
  content:''; position:absolute; inset:0;
  background: rgba(0,0,0,0.25); /* 稍微压暗背景，让文字更清晰 */
}
.hero-content { max-width: 900px; padding: 20px; }
.hero-badge {
  display: inline-block; font-size: 0.65rem; letter-spacing: 0.2em;
  border: 1px solid rgba(255,255,255,0.4); padding: 6px 16px;
  border-radius: 30px; margin-bottom: 25px; text-transform: uppercase;
}
.hero h1 {
  font-family: 'Cormorant Garamond', serif;
  font-size: clamp(3.5rem, 8vw, 6rem); font-weight: 300; line-height: 1.1;
  margin-bottom: 20px;
}
.hero h1 em { font-style: italic; }
.btn-main {
  display: inline-block; padding: 16px 40px; background: #fff; color: var(--text);
  text-decoration: none; border-radius: 50px; font-size: 0.75rem; letter-spacing: 0.15em;
  text-transform: uppercase; transition: 0.4s; margin-top: 30px;
}
.btn-main:hover { background: var(--gold); color: #fff; transform: translateY(-3px); }

/* 3. 评价区：三列布局 + Hover 变沙色 */
.reviews-section { padding: 120px 6%; background: var(--warm-white); }
.section-title {
  text-align: center; font-family: 'Cormorant Garamond', serif;
  font-size: 2.5rem; margin-bottom: 60px; font-weight: 300;
}
.reviews-grid {
  display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2px; /* 细线分隔感 */
}
.r-card {
  background: var(--cream); padding: 50px 40px;
  transition: all 0.4s ease; cursor: pointer;
}
.r-card:hover {
  background: var(--sand); /* 我们讨论的沙色 */
  transform: translateY(-5px);
}
.r-text {
  font-family: 'Cormorant Garamond', serif;
  font-size: 1.15rem; font-style: italic; margin-bottom: 25px;
}
.r-from { font-size: 0.7rem; letter-spacing: 0.15em; text-transform: uppercase; color: var(--light); }

/* 4. 背书区 (Grant Hazell) - 自然融入 */
.endorse-section {
  padding: 100px 6%; display: grid; grid-template-columns: 1fr 1fr;
  background: var(--cream); gap: 80px; align-items: center;
}
.endorse-quote {
  font-family: 'Cormorant Garamond', serif; font-size: 1.8rem;
  font-style: italic; line-height: 1.6;
}

/* 5. 结尾 CTA：大图叠白字 */
.cta-section {
  height: 70vh; position: relative;
  display: flex; align-items: center; justify-content: center;
  text-align: center; color: #fff;
}
.cta-bg {
  position: absolute; inset:0; z-index: -1;
  background: url('footer.jpg') center/cover no-repeat fixed; /* 固定背景增加高级感 */
}
.cta-bg::after { content:''; position:absolute; inset:0; background: rgba(0,0,0,0.4); }
.cta-content h2 { font-family: 'Cormorant Garamond', serif; font-size: 3rem; margin-bottom: 20px; }

/* 响应式 */
@media(max-width: 860px) {
  .endorse-section { grid-template-columns: 1fr; }
  .hero h1 { font-size: 3rem; }
}
</style>
</head>

<body>

<nav id="nav">
  <a href="#" class="nav-logo">That Gentle Door</a>
  <ul class="nav-links">
    <li><a href="#about">The Book</a></li>
    <li><a href="#readers">Reader Stories</a></li>
    <li><a href="#buy">Order Now</a></li>
  </ul>
</nav>

<section class="hero">
  <div class="hero-bg"></div>
  <div class="hero-content">
    <span class="hero-badge">✦ APLB Recommended Reading List</span>
    <h1><em>That Gentle</em><br>Door</h1>
    <p style="letter-spacing: 0.3em; font-size: 0.8rem; margin-top: 10px; opacity: 0.8;">MIVIMIKA LU</p>
    <a href="#buy" class="btn-main">Begin Healing</a>
  </div>
</section>

<section id="about" class="endorse-section">
  <div class="endorse-text">
    <p style="font-size: 0.65rem; letter-spacing: 0.2em; color: var(--gold); margin-bottom: 15px;">EXPERT ENDORSEMENT</p>
    <div class="endorse-quote">
      "This book doesn't promise a cure for your heartache. Instead, it offers companionship through the wilderness."
    </div>
    <p style="margin-top: 25px; font-size: 0.75rem; letter-spacing: 0.1em;">GRANT HAZELL · THE PET LOSS WAYFINDER</p>
  </div>
  <div class="endorse-img">
    <img src="book.jpg" alt="Book Cover" style="width: 100%; border-radius: 2px; box-shadow: 0 20px 40px rgba(0,0,0,0.1);">
  </div>
</section>

<section id="readers" class="reviews-section">
  <h3 class="section-title">Words from the Heart</h3>
  <div class="reviews-grid">
    <div class="r-card">
      <p class="r-text">"Helped me more than the writer could ever know. Made my perspective so much clearer and better."</p>
      <p class="r-from">CHARMAINE · UNITED KINGDOM</p>
    </div>
    <div class="r-card">
      <p class="r-text">"A truly special book. Such a powerful and beautiful read at a time of great loss."</p>
      <p class="r-from">SARAH D. · VERIFIED PURCHASE</p>
    </div>
    <div class="r-card">
      <p class="r-text">"Your love was enough. It was always enough. And the fact that it hurts this much is proof."</p>
      <p class="r-from">FROM THE EPILOGUE</p>
    </div>
  </div>
</section>

<section id="buy" class="cta-section">
  <div class="cta-bg"></div>
  <div class="cta-content">
    <h2>The door is always open.</h2>
    <p style="margin-bottom: 40px; font-style: italic; opacity: 0.9;">Available now in Kindle & Paperback</p>
    <a href="https://www.amazon.com/That-Gentle-Door-Understanding-Goodbye/dp/B0GJNFJV7S" class="btn-main">Buy on Amazon</a>
  </div>
</section>

<script>
// 导航栏滚动交互
const nav = document.getElementById('nav');
window.addEventListener('scroll', () => {
  if (window.scrollY > 100) {
    nav.classList.add('scrolled');
  } else {
    nav.classList.remove('scrolled');
  }
});
</script>

</body>
</html>
