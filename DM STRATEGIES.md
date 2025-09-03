<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Digital Marketing & Its Types</title>
  <meta name="description" content="What is digital marketing? Learn the main types: Social Media, SEM, SEO, Content, and Email Marketing — with short explanations and examples." />
  <meta name="robots" content="index, follow" />

  <!-- 🔹 Paste your Google Search Console meta tag here (if you have it):
  <meta name="google-site-verification" content="your-verification-code" />
  -->

  <style>
    :root{
      --bg:#f6f8fb;
      --card:#ffffff;
      --accent:#0b6cff;
      --text:#1f2937;
      --muted:#536077;
      --radius:10px;
      --gap:18px;
    }
    *{box-sizing:border-box}
    body{margin:0;font-family:Inter,system-ui,Segoe UI,Roboto,Arial;color:var(--text);background:var(--bg);line-height:1.6}
    a{color:var(--accent);text-decoration:none}
    a:hover{text-decoration:underline}
    .container{max-width:920px;margin:28px auto;padding:20px}
    header{background:linear-gradient(90deg,#071233,#082f5b);color:white;padding:18px 20px;border-radius:12px}
    header .brand{font-weight:700;font-size:1.25rem}
    nav{margin-top:8px}
    nav a{margin-right:12px;color:#e6f0ff;font-weight:600}
    main{margin-top:var(--gap)}
    .card{background:var(--card);padding:18px;border-radius:var(--radius);box-shadow:0 6px 22px rgba(15,23,42,0.06);margin-bottom:var(--gap)}
    h1{margin:0;font-size:1.6rem}
    h2{margin-top:0;color:var(--accent)}
    .muted{color:var(--muted)}
    ul.types{padding-left:20px}
    .type{margin:12px 0;padding:12px;border-left:4px solid #e6f3ff;background:#fbfdff;border-radius:8px}
    footer{margin-top:12px;padding:14px;text-align:center;color:var(--muted);font-size:.95rem}
    @media (max-width:640px){
      .container{padding:14px}
      header{padding:14px}
    }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <div class="brand">Digital Marketing & Its Types</div>
      <nav aria-label="Main navigation">
        <a href="#what">What is Digital Marketing?</a>
        <a href="#types">Types</a>
        <a href="#examples">Examples</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <main class="container" id="main">
    <article id="what" class="card" aria-labelledby="what-heading">
      <h1 id="what-heading">What is Digital Marketing?</h1>
      <p class="muted">
        In today's world, digital marketing is essential for businesses to grow and build an online presence.
        Digital marketing defines your identity in customers' minds through advertising, organic methods (SEO),
        content marketing, email marketing, and social media platforms (Facebook, LinkedIn, Instagram).
      </p>
    </article>

    <section id="types" class="card" aria-labelledby="types-heading">
      <h2 id="types-heading">Types Of Digital Marketing</h2>

      <ul class="types" aria-label="Digital marketing types list">
        <li class="type"><strong>1) Social Media Marketing (SMM)</strong>
          <p class="muted">Social media platforms help connect your brand to potential customers via Facebook, Instagram, LinkedIn, and YouTube. These channels allow you to build awareness, engage audiences, and grow a community interested in your brand.</p>
        </li>

        <li class="type"><strong>2) Search Engine Marketing (Paid Advertising)</strong>
          <p class="muted">Search Engine Marketing (SEM) includes paid advertising such as Meta Ads (Facebook & Instagram), PPC campaigns, and YouTube Ads. These campaigns help you reach a wider audience, build funnels, and generate interest quickly.</p>
        </li>

        <li class="type"><strong>3) Search Engine Optimization (SEO)</strong>
          <p class="muted">SEO stands for Search Engine Optimization. It helps you optimize content and technical site elements so search engines (Google, Bing, Yahoo) can index your pages. Good SEO improves visibility and increases the chance of ranking higher on the Search Engine Results Page (SERP).</p>
        </li>

        <li class="type"><strong>4) Content Marketing</strong>
          <p class="muted">Content marketing focuses on creating valuable content (blogs, videos, infographics) and user-generated content (UGC) that attracts your audience, builds authority for your website, and improves your chances of ranking higher in search results.</p>
        </li>

        <li class="type"><strong>5) Email Marketing</strong>
          <p class="muted">Email marketing lets you land directly in a person's inbox to inform them about new products or services, share discounts, and provide personalized value. When done well, email feels personal and drives engagement and conversions.</p>
        </li>
      </ul>
    </section>

    <section id="examples" class="card" aria-labelledby="examples-heading">
      <h2 id="examples-heading">Short Examples & Uses</h2>
      <p class="muted"><strong>Social Media:</strong> Use short videos, posts, and ads to build awareness and collect leads.</p>
      <p class="muted"><strong>SEM / PPC:</strong> Run targeted campaigns to get instant traffic to special offers or landing pages.</p>
      <p class="muted"><strong>SEO:</strong> Optimize titles, headings, content, and technical site settings to appear for relevant searches.</p>
      <p class="muted"><strong>Content:</strong> Publish helpful guides and case studies that answer users' questions and build trust.</p>
      <p class="muted"><strong>Email:</strong> Send welcome sequences, product updates, and exclusive offers to subscribers.</p>
    </section>

    <section id="contact" class="card" aria-labelledby="contact-heading">
      <h2 id="contact-heading">Contact</h2>
      <p class="muted">Email: <a href="mailto:you@example.com">you@example.com</a></p>
      <p class="muted">Follow: <a href="#">Facebook</a> · <a href="#">LinkedIn</a></p>
    </section>
  </main>

  <footer role="contentinfo">
    <div class="container">
      <small>© <span id="year"></span> Digital Marketing & Its Types. All rights reserved.</small>
    </div>
  </footer>

  <script>
    // Auto-update year
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
