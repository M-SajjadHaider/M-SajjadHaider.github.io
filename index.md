---
layout: default
title: Home
---

<style>
  body {
    background: #f8fafc;
    color: #0f172a;
    font-family: 'Segoe UI', sans-serif;
  }

  .hero {
    background: #ffffff;
    border-radius: 20px;
    padding: 70px 40px;
    text-align: center;
    margin-bottom: 40px;
    border: 1px solid #e2e8f0;
    box-shadow: 0 10px 30px rgba(0,0,0,0.08);
  }

  .hero h1 {
    font-size: 42px;
    margin-bottom: 10px;
    color: #2563eb;
  }

  .hero p {
    font-size: 18px;
    color: #475569;
  }

  /* 4 COLUMN GRID */
  .info-cards {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px;
  }

  /* Tablet */
  @media (max-width: 992px) {
    .info-cards {
      grid-template-columns: repeat(2, 1fr);
    }
  }

  /* Mobile */
  @media (max-width: 576px) {
    .info-cards {
      grid-template-columns: 1fr;
    }
  }

  .card {
    background: #ffffff;
    border-radius: 15px;
    padding: 25px;
    text-align: center;
    border: 1px solid #e2e8f0;
    transition: 0.3s;
    box-shadow: 0 5px 20px rgba(0,0,0,0.05);
  }

  .card:hover {
    transform: translateY(-6px);
    box-shadow: 0 12px 30px rgba(37,99,235,0.15);
  }

  .card .icon {
    font-size: 32px;
    margin-bottom: 10px;
  }

  .card h3 {
    font-size: 14px;
    color: #64748b;
    margin-bottom: 5px;
  }

  .card p {
    font-size: 16px;
    font-weight: bold;
    color: #0f172a;
  }
</style>

<div class="hero">
  <h1>Sajjad Haider</h1>
  <p>Computer Engineering Student</p>
  <p>University of Engineering & Technology (UET) Faisalabad</p>
</div>

<div class="info-cards">
  <div class="card">
    <div class="icon">🎓</div>
    <h3>Degree</h3>
    <p>BS Computer Engineering</p>
  </div>

  <div class="card">
    <div class="icon">🏛️</div>
    <h3>University</h3>
    <p>UET Faisalabad</p>
  </div>

  <div class="card">
    <div class="icon">🏙️</div>
    <h3>Home City</h3>
    <p>Mian Channu</p>
  </div>

  <div class="card">
    <div class="icon">📅</div>
    <h3>Semester</h3>
    <p>1st Semester</p>
  </div>
</div>
