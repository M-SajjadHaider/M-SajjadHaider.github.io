<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width,initial-scale=1.0"/>
<title>Blog | Sajjad Haider</title>
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@700;800&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet"/>
<style>
*,*::before,*::after{margin:0;padding:0;box-sizing:border-box}
:root{
  --bg:#0d0f1a;--bg2:#141726;--bg3:#1a1f35;
  --accent:#ff4d6d;--accent2:#ff8fa3;
  --tw:#f0f2ff;--tm:#8a90b0;
  --nav:rgba(13,15,26,0.97);--br:rgba(255,77,109,0.15);
}
html,body{min-height:100%;font-family:'DM Sans',sans-serif;background:var(--bg);color:var(--tw)}

nav{
  position:fixed;top:0;left:0;right:0;z-index:100;
  background:var(--nav);backdrop-filter:blur(14px);
  border-bottom:1px solid var(--br);
  display:flex;align-items:center;justify-content:space-between;
  padding:0 6%;height:62px;
}
.logo{font-family:'Syne',sans-serif;font-weight:800;font-size:1.2rem;color:var(--accent);text-decoration:none}
.nav-links{display:flex;gap:2rem;list-style:none}
.nav-links a{
  color:var(--tm);text-decoration:none;font-size:0.92rem;
  padding:6px 0;position:relative;transition:color 0.2s;
}
.nav-links a::after{
  content:'';position:absolute;bottom:-2px;left:0;
  width:0;height:2px;background:var(--accent);
  border-radius:2px;transition:width 0.25s;
}
.nav-links a:hover,.nav-links a.active{color:var(--accent)}
.nav-links a.active::after,.nav-links a:hover::after{width:100%}

main{
  min-height:100vh;padding:110px 6% 60px;
}

.sec-title{
  font-family:'Syne',sans-serif;font-size:2rem;font-weight:800;
  color:var(--accent);margin-bottom:2.5rem;
  display:flex;align-items:center;gap:1rem;
}
.sec-title::before{content:'';display:block;width:5px;height:2rem;background:var(--accent);border-radius:3px}

.timeline{
  position:relative;
  padding-left:3rem;
  max-width:780px;
}
.timeline::before{
  content:'';position:absolute;left:18px;top:0;bottom:0;
  width:2px;background:linear-gradient(180deg,var(--accent),rgba(255,77,109,0.1));
  border-radius:2px;
}

.tl-item{
  position:relative;
  margin-bottom:2.2rem;
}
.tl-dot{
  position:absolute;left:-2.45rem;top:1.1rem;
  width:18px;height:18px;border-radius:50%;
  background:var(--bg);border:2px solid var(--accent);
  display:flex;align-items:center;justify-content:center;
  font-size:0.65rem;z-index:1;
  box-shadow:0 0 10px rgba(255,77,109,0.4);
}

.card{
  background:var(--bg2);border:1px solid var(--br);
  border-radius:16px;padding:1.6rem 1.8rem;
  transition:transform 0.2s, box-shadow 0.2s, border-color 0.2s;
}
.card:hover{
  transform:translateY(-3px);
  box-shadow:0 8px 30px rgba(255,77,109,0.12);
  border-color:rgba(255,77,109,0.35);
}

.card-header{
  display:flex;align-items:center;gap:0.9rem;
  margin-bottom:1rem;
}
.card-icon{
  width:44px;height:44px;border-radius:12px;
  background:rgba(255,77,109,0.1);border:1px solid var(--br);
  display:flex;align-items:center;justify-content:center;
  font-size:1.3rem;flex-shrink:0;
}
.card-title{
  font-family:'Syne',sans-serif;font-size:1.05rem;font-weight:700;
  color:var(--tw);
}
.card-badge{
  display:inline-block;font-size:0.7rem;font-weight:600;
  padding:2px 10px;border-radius:20px;letter-spacing:0.5px;
  background:rgba(255,77,109,0.12);color:var(--accent);
  border:1px solid rgba(255,77,109,0.25);margin-left:0.5rem;
  vertical-align:middle;
}

.card p{
  color:#bfc5e0;font-size:0.93rem;line-height:1.7;margin-bottom:0.5rem;
}
.card p:last-child{margin-bottom:0}

.targets-list{
  list-style:none;display:flex;flex-direction:column;gap:0.5rem;margin-top:0.3rem;
}
.targets-list li{
  display:flex;align-items:flex-start;gap:0.6rem;
  color:#bfc5e0;font-size:0.93rem;line-height:1.6;
}
.targets-list li::before{
  content:'→';color:var(--accent);font-weight:700;flex-shrink:0;margin-top:1px;
}

footer{
  margin-top:3rem;padding-top:2rem;
  text-align:center;color:var(--tm);font-size:0.85rem;
  border-top:1px solid var(--br);
  max-width:780px;
}
</style>
</head>
<body>

<nav>
  <a class="logo" href="index.html">Sajjad Haider</a>
  <ul class="nav-links">
    <li><a href="index.html">Home</a></li>
    <li><a href="about.html">About</a></li>
    <li><a href="blog.html" class="active">Blog</a></li>
    <li><a href="contact.html">Contact</a></li>
  </ul>
</nav>

<main>
  <h2 class="sec-title">My Blog</h2>

  <div class="timeline">

    <!-- Journey -->
    <div class="tl-item">
      <div class="tl-dot">🚀</div>
      <div class="card">
        <div class="card-header">
          <div class="card-icon">🚀</div>
          <span class="card-title">My Journey in Tech</span>
        </div>
        <p>Welcome to my blog. Here I share my thoughts, projects, and experiences.</p>
        <p>I am a student of Computer Engineering. I love to learn new things and build projects.</p>
        <p>I have done my Intermediate with ICS (Computer Science) before joining Computer Engineering.</p>
      </div>
    </div>

    <!-- Admission -->
    <div class="tl-item">
      <div class="tl-dot">🎓</div>
      <div class="card">
        <div class="card-header">
          <div class="card-icon">🎓</div>
          <span class="card-title">Admission at UET <span class="card-badge">UET</span></span>
        </div>
        <p>I got admission in Computer Engineering at UET — one of Pakistan's top engineering universities.</p>
        <p>It was a tough journey preparing for the entry test, but hard work and dedication paid off.</p>
      </div>
    </div>

    <!-- 1st Semester -->
    <div class="tl-item">
      <div class="tl-dot">📘</div>
      <div class="card">
        <div class="card-header">
          <div class="card-icon">📘</div>
          <span class="card-title">1st Semester at UET <span class="card-badge">Semester 1</span></span>
        </div>
        <p>First semester was full of challenges and new learning. New subjects, new environment, new friends.</p>
        <p>I worked hard on my PIN projects and learned the basics of engineering courses.</p>
        <p>Our semester project was based on <strong>Machine Learning</strong> — exploring how machines learn from data and make intelligent decisions.</p>
      </div>
    </div>

    <!-- 2nd Semester -->
    <div class="tl-item">
      <div class="tl-dot">📗</div>
      <div class="card">
        <div class="card-header">
          <div class="card-icon">📗</div>
          <span class="card-title">2nd Semester at UET <span class="card-badge">Semester 2</span></span>
        </div>
        <p>Second semester brought more advanced topics and deeper understanding of Computer Engineering.</p>
        <p>I continued building projects and improving my programming and web development skills.</p>
      </div>
    </div>

    <!-- Targets -->
    <div class="tl-item">
      <div class="tl-dot">🎯</div>
      <div class="card">
        <div class="card-header">
          <div class="card-icon">🎯</div>
          <span class="card-title">My Targets</span>
        </div>
        <ul class="targets-list">
          <li>Complete First Semester at UET with good grades</li>
          <li>Submit all First Semester PIN Projects at UET successfully</li>
          <li>Learn Web Development and build my own portfolio</li>
          <li>Contribute to GitHub projects regularly</li>
        </ul>
      </div>
    </div>

  </div>

  <footer>&copy; 2025 Sajjad Haider. All Rights Reserved.</footer>
</main>

</body>
</html>
