<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Blog | Sajjad Haider</title>

<link href="https://fonts.googleapis.com/css2?family=Syne:wght@700;800&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet">

<style>
body{
  margin:0;
  font-family:'DM Sans',sans-serif;
  background:#0d0f1a;
  color:white;
}

/* NAVBAR */
nav{
  position:fixed;
  top:0;
  width:100%;
  background:#0d0f1a;
  padding:15px 30px;
  display:flex;
  justify-content:space-between;
}

nav a{
  color:#aaa;
  text-decoration:none;
  margin-left:20px;
}

nav a:hover{
  color:#ff4d6d;
}

/* MAIN */
main{
  padding:100px 20px;
}

h2{
  color:#ff4d6d;
}

/* CARD */
.card{
  background:#141726;
  padding:20px;
  margin-bottom:20px;
  border-radius:10px;
  border:1px solid rgba(255,77,109,0.2);
}

.card h3{
  margin-top:0;
  color:white;
}

.card p{
  color:#ccc;
}
</style>
</head>

<body>

<nav>
  <div>Sajjad Haider</div>
  <div>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Blog</a>
    <a href="#">Contact</a>
  </div>
</nav>

<main>

<h2>My Blog</h2>

<div class="card">
  <h3>🚀 My Journey in Tech</h3>
  <p>I am a Computer Engineering student. I love building projects and learning new technologies.</p>
</div>

<div class="card">
  <h3>🎓 Admission at UET</h3>
  <p>I got admission in Computer Engineering after hard work and preparation.</p>
</div>

<div class="card">
  <h3>📘 1st Semester</h3>
  <p>Learned basics of engineering and worked on Machine Learning project.</p>
</div>

<div class="card">
  <h3>📗 2nd Semester</h3>
  <p>Improved programming and web development skills.</p>
</div>

</main>

</body>
</html>
