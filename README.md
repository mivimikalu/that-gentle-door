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
:root {
  --cream: #f7f3ec;
  --warm-white: #fdfaf5;
  --sand: #e6dfd1;
  --gold: #c9a96e;
  --text: #2a2520;
  --mid: #6b5f52;
  --light: #a99e94;
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

/* NAV */
nav {
  position: fixed; top:0; left:0; right:0; z-index:1000;
  padding: 25px 6%;
  display: flex; justify-content: space-between; align-items: center;
  transition: all 0.5s ease;
}
nav.scrolled {
  background: rgba(255,255,255,0.8);
  backdrop-filter: blur(15px);
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

/* HERO */
.hero {
  position: relative; height: 100vh;
  display: flex; align-items: center; justify-content: center;
  text-align: center; color: #fff; overflow: hidden;
}
.hero-bg {
  position: absolute; inset:0; z-index: 0;
}
.hero-bg img {
  width: 100%; height: 100%; object-fit: cover; object-position: center;
}
.hero-bg::after {
  content:''; position:absolute; inset:0;
  background: rgba(0,0,0,0.3);
}
.hero-content {
  position: relative; z-index: 1;
  max-width: 900px; padding: 20px;
}
.hero-badge {
  display: inline-block; font-size: 0.65rem; letter-spacing: 0.2em;
  border: 1px solid rgba(255,255,255,0.4); padding: 6px 16px;
  border-radius: 30px; margin-bottom: 25px; text-transform: uppercase;
}
.hero h1 {
  font-family: 'Cormorant Garamond', serif;
  font-size: clamp(3.5rem, 8vw, 6.5rem); font-weight: 300; line-height: 1.05;
  margin-bottom: 16px;
}
.hero h1 em { font-style: italic; }
.hero-sub {
  font-family: 'Cormorant Garamond', serif;
  font-size: 1.1rem; font-style: italic; font-weight: 300;
  opacity: 0.85; margin-bottom: 8px;
}
.hero-author {
  font-size: 0.7rem; letter-spacing: 0.3em; text-transform: uppercase;
  opacity: 0.65; margin-bottom: 36px;
}
.btn-main {
  display: inline-block; padding: 15px 38px; background: #fff; color: var(--text);
  text-decoration: none; border-radius: 50px; font-size: 0.72rem; letter-spacing: 0.15em;
  text-transform: uppercase; transition: 0.4s; margin: 6px;
}
.btn-main:hover { background: var(--gold); color: #fff; transform: translateY(-3px); }
.btn-ghost {
  display: inline-block; padding: 15px 38px;
  border: 1px solid rgba(255,255,255,0.5); color: #fff;
  text-decoration: none; border-radius: 50px; font-size: 0.72rem; letter-spacing: 0.15em;
  text-transform: uppercase; transition: 0.4s; margin: 6px;
}
.btn-ghost:hover { border-color: #fff; background: rgba(255,255,255,0.1); }

/* INTRO */
.intro-section {
  padding: 100px 6%;
  display: grid; grid-template-columns: 1fr 1fr;
  gap: 80px; align-items: center;
  background: var(--warm-white);
}
.intro-text h2 {
  font-family: 'Cormorant Garamond', serif;
  font-size: clamp(1.8rem, 3vw, 2.6rem); font-weight: 300; line-height: 1.3;
  color: var(--gold); margin-bottom: 28px;
}
.intro-text p {
  font-size: 0.9rem; color: var(--mid); line-height: 1.95; margin-bottom: 16px;
}
.intro-text .verse {
  font-family: 'Cormorant Garamond', serif;
  font-size: 1rem; font-style: italic;
  border-left: 1px solid var(--gold);
  padding: 16px 0 16px 22px;
  color: var(--text); line-height: 1.8;
  margin: 28px 0;
}
.intro-img {
  position: relative;
}
.intro-img img {
  width: 100%; border-radius: 2px;
  box-shadow: 20px 24px 50px rgba(42,37,32,0.15);
}

/* WHAT'S INSIDE */
.inside-section {
  padding: 100px 6%;
  background: var(--cream);
}
.inside-section .s-label {
  font-size: 0.65rem; letter-spacing: 0.22em; text-transform: uppercase;
  color: var(--gold); margin-bottom: 10px;
}
.inside-section h2 {
  font-family: 'Cormorant Garamond', serif;
  font-size: clamp(2rem, 3.5vw, 3rem); font-weight: 300;
  margin-bottom: 60px;
}
.inside-section h2 em { font-style: italic; color: var(--gold); }
.questions-grid {
  display: grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 2px; margin-bottom: 60px;
}
.q-card {
  background: var(--warm-white);
  padding: 36px 30px;
  transition: background 0.3s, transform 0.3s;
}
.q-card:hover { background: var(--sand); transform: translateY(-3px); }
.q-card .q-num {
  font-family: 'Cormorant Garamond', serif;
  font-size: 2.5rem; font-weight: 300; color: var(--gold);
  opacity: 0.4; line-height: 1; margin-bottom: 12px;
}
.q-card h3 {
  font-family: 'Cormorant Garamond', serif;
  font-size: 1.05rem; font-style: italic; font-weight: 400;
  color: var(--text); margin-bottom: 10px;
}
.q-card p { font-size: 0.83rem; color: var(--mid); line-height: 1.8; }

.integrates {
  display: grid; grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
  gap: 2px; margin-top: 20px;
}
.integrate-item {
  background: var(--warm-white); padding: 28px 24px;
  text-align: center;
  transition: background 0.3s;
}
.integrate-item:hover { background: var(--sand); }
.integrate-item .i-icon {
  font-size: 1.4rem; margin-bottom: 10px; display: block;
}
.integrate-item h4 {
  font-family: 'Cormorant Garamond', serif;
  font-size: 0.95rem; font-weight: 400; margin-bottom: 6px;
}
.integrate-item p { font-size: 0.75rem; color: var(--mid); }

/* ENDORSEMENT */
.endorse-section {
  padding: 100px 6%; display: grid; grid-template-columns: 1fr 1fr;
  background: var(--sand); gap: 80px; align-items: center;
}
.endorse-label {
  font-size: 0.65rem; letter-spacing: 0.2em; text-transform: uppercase;
  color: var(--mid); margin-bottom: 16px;
}
.endorse-quote {
  font-family: 'Cormorant Garamond', serif;
  font-size: clamp(1.3rem, 2.2vw, 1.75rem);
  font-style: italic; line-height: 1.65; color: var(--text);
  margin-bottom: 28px;
}
.endorse-credit {
  font-size: 0.72rem; letter-spacing: 0.14em; text-transform: uppercase;
  color: var(--mid); line-height: 1.8;
}
.endorse-badges {
  display: flex; flex-direction: column; gap: 10px; margin-top: 28px;
}
.badge {
  display: flex; align-items: flex-start; gap: 12px;
  background: rgba(255,255,255,0.5); padding: 14px 18px; border-radius: 2px;
  font-size: 0.8rem; color: var(--mid); line-height: 1.5;
}
.badge-icon { font-size: 1rem; flex-shrink: 0; margin-top: 2px; }
.endorse-img img {
  width: 100%; border-radius: 2px;
  box-shadow: 16px 20px 48px rgba(42,37,32,0.12);
}

/* REVIEWS */
.reviews-section { padding: 100px 6%; background: var(--warm-white); }
.reviews-header {
  display: grid; grid-template-columns: 1fr 1fr;
  gap: 60px; align-items: end; margin-bottom: 48px;
}
.reviews-header h2 {
  font-family: 'Cormorant Garamond', serif;
  font-size: clamp(2rem, 3.5vw, 3rem); font-weight: 300; line-height: 1.2;
}
.reviews-header h2 em { font-style: italic; color: var(--gold); }
.reviews-header p { font-size: 0.87rem; color: var(--mid); line-height: 1.9; }
.reviews-grid {
  display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 2px;
}
.r-card {
  background: var(--cream); padding: 44px 36px;
  transition: all 0.4s ease;
}
.r-card:hover { background: var(--sand); transform: translateY(-4px); }
.r-stars { color: var(--gold); font-size: 0.65rem; letter-spacing: 3px; margin-bottom: 18px; }
.r-text {
  font-family: 'Cormorant Garamond', serif;
  font-size: 1.12rem; font-style: italic; line-height: 1.8;
  color: var(--text); margin-bottom: 20px;
}
.r-from {
  font-size: 0.68rem; letter-spacing: 0.12em; text-transform: uppercase; color: var(--light);
}

/* FOR YOU */
.foryou-section {
  padding: 100px 6%;
  background: var(--cream);
  display: grid; grid-template-columns: 1fr 1fr;
  gap: 80px; align-items: center;
}
.foryou-img { position: relative; overflow: hidden; border-radius: 2px; }
.foryou-img img { width: 100%; display: block; transition: transform 0.5s; }
.foryou-img:hover img { transform: scale(1.03); }
.foryou-text .s-label {
  font-size: 0.65rem; letter-spacing: 0.22em; text-transform: uppercase;
  color: var(--gold); margin-bottom: 16px;
}
.foryou-text h2 {
  font-family: 'Cormorant Garamond', serif;
  font-size: clamp(1.8rem, 3vw, 2.6rem); font-weight: 300; line-height: 1.3;
  margin-bottom: 28px;
}
.foryou-text h2 em { font-style: italic; color: var(--gold); }
.foryou-list { list-style: none; border-top: 1px solid var(--border); }
.foryou-list li {
  padding: 13px 0; border-bottom: 1px solid var(--border);
  font-size: 0.87rem; color: var(--mid);
  display: flex; gap: 14px; align-items: flex-start;
}
.foryou-list li::before { content: '–'; color: var(--gold); flex-shrink: 0; }

/* CTA */
.cta-section {
  height: 70vh; position: relative;
  display: flex; align-items: center; justify-content: center;
  text-align: center; color: #fff; overflow: hidden;
}
.cta-bg {
  position: absolute; inset:0; z-index: 0;
}
.cta-bg img { width: 100%; height: 100%; object-fit: cover; }
.cta-bg::after { content:''; position:absolute; inset:0; background: rgba(0,0,0,0.45); }
.cta-content { position: relative; z-index: 1; max-width: 640px; padding: 20px; }
.cta-content h2 {
  font-family: 'Cormorant Garamond', serif;
  font-size: clamp(2rem, 4.5vw, 3.5rem); font-weight: 300; font-style: italic;
  line-height: 1.3; margin-bottom: 10px;
}
.cta-content p { font-style: italic; opacity: 0.8; margin-bottom: 40px; font-size: 0.9rem; }
.cta-btns { display: flex; gap: 12px; justify-content: center; flex-wrap: wrap; }

/* FOOTER */
footer {
  padding: 44px 6%; background: var(--text);
  display: flex; justify-content: space-between; align-items: center;
  flex-wrap: wrap; gap: 20px;
}
.footer-logo {
  font-family: 'Cormorant Garamond', serif;
  font-size: 1rem; font-style: italic; color: rgba(255,255,255,0.5);
}
.footer-links { display: flex; gap: 24px; flex-wrap: wrap; }
.footer-links a {
  font-size: 0.68rem; letter-spacing: 0.14em; text-transform: uppercase;
  color: rgba(255,255,255,0.35); text-decoration: none; transition: color 0.3s;
}
.footer-links a:hover { color: var(--gold); }
.footer-copy {
  width: 100%; text-align: center; font-size: 0.65rem;
  color: rgba(255,255,255,0.2); margin-top: 16px; padding-top: 20px;
  border-top: 1px solid rgba(255,255,255,0.07);
}

/* REVEAL */
.reveal { opacity:0; transform:translateY(24px); transition:opacity 0.85s ease,transform 0.85s ease; }
.reveal.on { opacity:1; transform:none; }
.reveal-l { opacity:0; transform:translateX(-24px); transition:opacity 0.85s ease,transform 0.85s ease; }
.reveal-l.on { opacity:1; transform:none; }
.reveal-r { opacity:0; transform:translateX(24px); transition:opacity 0.85s ease,transform 0.85s ease; }
.reveal-r.on { opacity:1; transform:none; }
@keyframes fadeUp { from{opacity:0;transform:translateY(32px);}to{opacity:1;transform:none;} }
.hero-content { animation: fadeUp 1.1s 0.2s ease both; }

/* RESPONSIVE */
@media(max-width:860px){
  nav .nav-links { display:none; }
  .intro-section, .endorse-section, .foryou-section { grid-template-columns:1fr; gap:40px; }
  .reviews-header { grid-template-columns:1fr; }
  footer { flex-direction:column; text-align:center; }
  .footer-links { justify-content:center; }
}
</style>
</head>
<body>

<!-- NAV -->
<nav id="nav">
  <a href="#" class="nav-logo">That Gentle Door</a>
  <ul class="nav-links">
    <li><a href="#about">The Book</a></li>
    <li><a href="#readers">Reader Stories</a></li>
    <li><a href="#buy">Order Now</a></li>
    <li><a href="https://www.tiktok.com/@lovemivi_" target="_blank">TikTok</a></li>
    <li><a href="https://substack.com/@mivimikalu/posts" target="_blank">Substack</a></li>
  </ul>
</nav>

<!-- HERO -->
<section class="hero">
  <div class="hero-bg">
    <!-- 图片名称：hero.jpg → 用你的 1000035053.png 改名为 hero.jpg -->
    <img src="hero.jpg" alt="A gentle path toward light">
  </div>
  <div class="hero-content">
    <span class="hero-badge">✦ APLB Recommended Reading List</span>
    <h1><em>That Gentle</em><br>Door</h1>
    <p class="hero-sub">Understanding Pet Loss, Love, and Life After Goodbye</p>
    <p class="hero-author">Mivimika Lu</p>
    <a href="https://www.amazon.com/That-Gentle-Door-Understanding-Goodbye/dp/B0GJNFJV7S" target="_blank" class="btn-main">Buy on Amazon US</a>
    <a href="https://www.amazon.co.uk/That-Gentle-Door-Understanding-Goodbye/dp/B0GJNFJV7S" target="_blank" class="btn-ghost">Amazon UK</a>
  </div>
</section>

<!-- INTRO -->
<section class="intro-section" id="about">
  <div class="intro-text reveal-l">
    <h2>When they cross that gentle door,<br>where do they go?</h2>
    <p>If you're holding this page, you may be grieving the loss of a beloved pet. The leash still hangs by the door. The bowl sits untouched. And the question that echoes through your days is one no one seems able to answer.</p>
    <p>That Gentle Door is a compassionate, thoughtful guide for anyone navigating pet loss, animal grief, or the death of a beloved companion. Unlike many pet loss books that rely on clichés or quick reassurances, this book respects both your intelligence and your pain.</p>
    <blockquote class="verse">
      "Energy cannot be destroyed. This is not metaphor — this is physics.<br>
      The warmth that once lived in their body is still here.<br>
      Not in the same form. But here."
    </blockquote>
    <p>Written with the tenderness of poetry and grounded in science, psychology, philosophy, and spirituality.</p>
  </div>
  <div class="intro-img reveal-r">
    <!-- 图片名称：book.jpg → 用你的 1000033478.jpg 改名为 book.jpg -->
    <img src="book.jpg" alt="That Gentle Door book cover">
  </div>
</section>

<!-- WHAT'S INSIDE -->
<section class="inside-section">
  <p class="s-label">Inside This Book</p>
  <h2>This book <em>answers</em> the questions<br>that truly matter</h2>
  <div class="questions-grid">
    <div class="q-card reveal">
      <div class="q-num">01</div>
      <h3>Why do I feel so guilty after my pet died?</h3>
      <p>Learn how sudden loss, euthanasia decisions, and accidents affect the grieving brain — and why guilt is not proof of failure, but evidence of love.</p>
    </div>
    <div class="q-card reveal">
      <div class="q-num">02</div>
      <h3>Was my pet's life too short?</h3>
      <p>Discover a powerful reframing of "short" lives as complete lives, helping release regret and self-blame.</p>
    </div>
    <div class="q-card reveal">
      <div class="q-num">03</div>
      <h3>Where do pets go after death?</h3>
      <p>Explore multiple perspectives — the Rainbow Bridge, energy conservation, and continued presence — offered gently, without demanding belief.</p>
    </div>
    <div class="q-card reveal">
      <div class="q-num">04</div>
      <h3>How do I keep living after losing my pet?</h3>
      <p>Find guidance on moving forward with love, not "moving on," and honoring your bond while continuing life.</p>
    </div>
  </div>

  <p style="font-size:0.65rem;letter-spacing:0.22em;text-transform:uppercase;color:var(--gold);margin-bottom:20px;">This Book Integrates</p>
  <div class="integrates">
    <div class="integrate-item reveal">
      <span class="i-icon">🧠</span>
      <h4>Neuroscience</h4>
      <p>Why grief feels physically unbearable</p>
    </div>
    <div class="integrate-item reveal">
      <span class="i-icon">💭</span>
      <h4>Psychology</h4>
      <p>How attachment and loss affect the mind</p>
    </div>
    <div class="integrate-item reveal">
      <span class="i-icon">⚛️</span>
      <h4>Physics</h4>
      <p>Energy conservation, explained simply</p>
    </div>
    <div class="integrate-item reveal">
      <span class="i-icon">🌿</span>
      <h4>Philosophy</h4>
      <p>Stoicism, impermanence, and meaning</p>
    </div>
    <div class="integrate-item reveal">
      <span class="i-icon">✨</span>
      <h4>Spirituality</h4>
      <p>The Rainbow Bridge, as one possible comfort</p>
    </div>
  </div>
</section>

<!-- ENDORSEMENT -->
<section class="endorse-section">
  <div class="reveal-l">
    <p class="endorse-label">Expert Endorsement</p>
    <blockquote class="endorse-quote">
      "This book doesn't promise a cure for your heartache. Instead, it offers companionship through the wilderness."
    </blockquote>
    <div class="endorse-badges">
      <div class="badge">
        <span class="badge-icon">📖</span>
        Featured on the Association for Pet Loss and Bereavement's Recommended Reading List
      </div>
      <div class="badge">
        <span class="badge-icon">✦</span>
        Highly recommended by APLB-Certified Pet Loss Grief Counselor
      </div>
    </div>
  </div>
  <div class="endorse-img reveal-r">
    <!-- 图片名称：endorse.jpg → 用你的 1000035049.png 改名为 endorse.jpg -->
    <img src="endorse.jpg" alt="Gentle light">
  </div>
</section>

<!-- REVIEWS -->
<section class="reviews-section" id="readers">
  <div class="reviews-header">
    <div class="reveal">
      <p style="font-size:0.65rem;letter-spacing:0.22em;text-transform:uppercase;color:var(--gold);margin-bottom:12px;">Reader Stories</p>
      <h2>Words from those who<br>have walked <em>this path</em></h2>
    </div>
    <p class="reveal">Real readers. Real grief. Real healing. Shared freely in pet loss communities — because sometimes, the most healing thing we can do is pass on what helped us.</p>
  </div>
  <div class="reviews-grid">
    <div class="r-card reveal">
      <div class="r-stars">★★★★★</div>
      <p class="r-text">"It has been very helpful. Easy to read and each time I read it I feel a little better."</p>
      <p class="r-from">Facebook Community</p>
    </div>
    <div class="r-card reveal">
      <div class="r-stars">★★★★★</div>
      <p class="r-text">"I read it in one sitting, bawling my eyes out. That book, and God, helped me more than you could ever know."</p>
      <p class="r-from">Facebook Community</p>
    </div>
    <div class="r-card reveal">
      <div class="r-stars">★★★★★</div>
      <p class="r-text">"It's an easy 85-page book that has helped me so much. I wish I knew about it earlier. I will read it again and again. If you need comfort, I highly recommend it."</p>
      <p class="r-from">Facebook Community</p>
    </div>
    <div class="r-card reveal">
      <div class="r-stars">★★★★★</div>
      <p class="r-text">"It gives you a more beautiful perspective of life. A part of me feels peace knowing he's at home again."</p>
      <p class="r-from">Facebook Community</p>
    </div>
    <div class="r-card reveal">
      <div class="r-stars">★★★★★</div>
      <p class="r-text">"Incredible read, it helped a lot."</p>
      <p class="r-from">Facebook Community</p>
    </div>
    <div class="r-card reveal">
      <div class="r-stars">★★★★★</div>
      <p class="r-text">"Helped me more than the writer could ever know. Made my perspective so much clearer and better."</p>
      <p class="r-from">Amazon UK · Verified Purchase</p>
    </div>
    <div class="r-card reveal">
      <div class="r-stars">★★★★★</div>
      <p class="r-text">"This is such a powerful and beautiful book. I am so glad I was drawn to ordering this at a time of great loss."</p>
      <p class="r-from">Amazon UK · Verified Purchase</p>
    </div>
  </div>
</section>

<!-- FOR YOU -->
<section class="foryou-section">
  <div class="foryou-img reveal-l">
    <!-- 图片名称：foryou.jpg → 用你的 1000035052.png 改名为 foryou.jpg -->
    <img src="foryou.jpg" alt="A gentle room with pets">
  </div>
  <div class="foryou-text reveal-r">
    <p class="s-label">This Book Is For You If</p>
    <h2>You loved an animal<br>with your <em>whole heart</em></h2>
    <ul class="foryou-list">
      <li>You are grieving the loss of a dog, cat, or other beloved pet</li>
      <li>You feel overwhelmed, numb, or like you are "losing your mind"</li>
      <li>You struggle with guilt, regret, or "what if" thoughts</li>
      <li>You want reassurance that your pet is not suffering</li>
      <li>You are unsure whether you can ever love another animal again</li>
      <li>You want a pet grief book that is thoughtful, intelligent, and emotionally honest</li>
      <li>"Just get another pet" is not an answer you can accept</li>
    </ul>
  </div>
</section>

<!-- CTA -->
<section class="cta-section" id="buy">
  <div class="cta-bg">
    <!-- 图片名称：cta.jpg → 用你的 1000035048.png 改名为 cta.jpg -->
    <img src="cta.jpg" alt="Golden light">
  </div>
  <div class="cta-content reveal">
    <h2>"Your love was enough.<br>It was always enough."</h2>
    <p>Available now in Kindle &amp; Paperback</p>
    <div class="cta-btns">
      <a href="https://www.amazon.com/That-Gentle-Door-Understanding-Goodbye/dp/B0GJNFJV7S" target="_blank" class="btn-main">Buy on Amazon US</a>
      <a href="https://www.amazon.co.uk/That-Gentle-Door-Understanding-Goodbye/dp/B0GJNFJV7S" target="_blank" class="btn-ghost">Amazon UK</a>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <span class="footer-logo">That Gentle Door · Mivimika Lu</span>
  <div class="footer-links">
    <a href="https://www.amazon.com/That-Gentle-Door-Understanding-Goodbye/dp/B0GJNFJV7S" target="_blank">Amazon US</a>
    <a href="https://www.amazon.co.uk/That-Gentle-Door-Understanding-Goodbye/dp/B0GJNFJV7S" target="_blank">Amazon UK</a>
    <a href="https://www.tiktok.com/@lovemivi_" target="_blank">TikTok</a> 
    <a href="https://substack.com/@mivimikalu/posts" target="_blank">Substack</a>
  </div>
  <p class="footer-copy">© 2026 Mivimika Lu · All rights reserved · Featured on the APLB Recommended Reading List</p>
</footer>

<script>
const nav = document.getElementById('nav');
window.addEventListener('scroll', () => {
  nav.classList.toggle('scrolled', window.scrollY > 80);
});
const io = new IntersectionObserver(entries => {
  entries.forEach((e, i) => {
    if (e.isIntersecting) setTimeout(() => e.target.classList.add('on'), i * 80);
  });
}, { threshold: 0.1 });
document.querySelectorAll('.reveal,.reveal-l,.reveal-r').forEach(el => io.observe(el));
</script>
</body>
</html>
