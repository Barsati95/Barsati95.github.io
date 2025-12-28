---
layout: default
title: Home
---

<style>
  .hero-section {
    background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%);
    color: white;
    padding: 80px 20px;
    text-align: center;
    border-radius: 20px;
    margin-bottom: 40px;
    box-shadow: 0 10px 20px rgba(0,0,0,0.2);
  }
  
  .logo-img {
    width: 120px; 
    height: 120px; 
    border-radius: 50%;
    margin-bottom: 20px;
    border: 4px solid white;
    background: white;
  }

  .nav-custom {
    display: flex;
    justify-content: center;
    gap: 25px;
    background: #ffffff;
    padding: 15px;
    border-radius: 50px;
    margin-bottom: 30px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);
    position: sticky;
    top: 10px;
    z-index: 1000;
  }

  .nav-custom a {
    text-decoration: none;
    color: #2a5298;
    font-weight: 700;
    font-size: 1.1em;
    transition: 0.3s;
  }

  .nav-custom a:hover {
    color: #ff8c00;
  }

  /* Card and Grid Styles remain similar but more polished */
  .subject-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 25px;
  }

  .subject-card {
    background: white;
    border-radius: 15px;
    overflow: hidden;
    box-shadow: 0 5px 15px rgba(0,0,0,0.08);
    transition: 0.3s;
  }

  .subject-card:hover {
    transform: translateY(-10px);
  }
</style>

<div class="nav-custom">
    <a href="./index.html">🏠 Home</a>
    <a href="./subjects.html">📚 Subjects</a>
    <a href="./about.html">🙋‍♂️ About</a>
</div>

<div class="hero-section">
    <img src="https://github.com/user-attachments/assets/54428106-4b55-46b7-8fa5-dc9a1774f7aa" alt="Studygrammarhub Logo" class="logo-img"> 
    
    <h1 style="font-size: 2.5em; margin: 0;">Studygrammarhub</h1>
    <p style="font-size: 1.2em; opacity: 0.9;">Master Grammar, Unlock Success.</p>
</div>

<style>
  /* Section Title Style */
  .section-title {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 30px 10px 15px;
    font-family: sans-serif;
  }
  .section-title h2 { font-size: 1.2rem; color: #333; margin: 0; }
  .view-all { 
    background: #f0fdf4; color: #16a34a; padding: 5px 12px; 
    border-radius: 5px; text-decoration: none; font-size: 0.8rem; font-weight: bold;
  }

  /* Subject Grid Layout */
  .grid-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr); /* Ek line mein 3 box */
    gap: 12px;
    padding: 10px;
  }

  /* Colorful Icon Box Style */
  .subject-box {
    background: #fff;
    border: 1px solid #eee;
    border-radius: 12px;
    padding: 15px 5px;
    text-align: center;
    text-decoration: none;
    transition: 0.3s;
    box-shadow: 0 2px 5px rgba(0,0,0,0.03);
  }
  .subject-box:hover { transform: translateY(-3px); box-shadow: 0 5px 15px rgba(0,0,0,0.1); }

  .icon-circle {
    width: 50px; height: 50px;
    margin: 0 auto 10px;
    display: flex; align-items: center; justify-content: center;
    font-size: 24px; border-radius: 12px;
  }

  .subject-name { color: #444; font-size: 0.8rem; font-weight: 600; display: block; }

  /* Colors for Icons (Matching the Image) */
  .bg-blue { background: #e0f2fe; color: #0369a1; }
  .bg-orange { background: #ffedd5; color: #c2410c; }
  .bg-purple { background: #f3e8ff; color: #7e22ce; }
  .bg-green { background: #dcfce7; color: #15803d; }
  .bg-red { background: #fee2e2; color: #b91c1c; }
  .bg-yellow { background: #fef9c3; color: #a16207; }
</style>

<div class="section-title">
  <h2>Grammar Sections</h2>
  <a href="#" class="view-all">सभी देखें</a>
</div>

<div class="grid-container">
  <a href="#" class="subject-box">
    <div class="icon-circle bg-blue">📝</div>
    <span class="subject-name">Tenses</span>
  </a>
  <a href="#" class="subject-box">
    <div class="icon-circle bg-orange">🗣️</div>
    <span class="subject-name">Active Voice</span>
  </a>
  <a href="#" class="subject-box">
    <div class="icon-circle bg-purple">📖</div>
    <span class="subject-name">Articles</span>
  </a>
</div>

<div class="section-title">
  <h2>Study Materials</h2>
  <a href="#" class="view-all">सभी देखें</a>
</div>

<div class="grid-container">
  <a href="#" class="subject-box">
    <div class="icon-circle bg-green">📚</div>
    <span class="subject-name">NCERT Book</span>
  </a>
  <a href="#" class="subject-box">
    <div class="icon-circle bg-red">💡</div>
    <span class="subject-name">Mind Maps</span>
  </a>
  <a href="#" class="subject-box">
    <div class="icon-circle bg-yellow">❓</div>
    <span class="subject-name">Imp. Ques.</span>
  </a>
</div>

    </div> 
    <footer style="background: #1e3c72; color: white; padding: 40px 20px; text-align: center; margin-top: 50px; border-radius: 20px 20px 0 0;">
    <div style="margin-bottom: 20px;">
        <h2 style="margin: 0;">StudyGrammarHub</h2>
        <p style="opacity: 0.8;">Quality Education for Everyone</p>
    </div>
    
    <div style="margin-bottom: 20px;">
        <a href="./about.html" style="color: white; margin: 0 10px; text-decoration: none;">About Us</a> | 
        <a href="mailto:aapkaemail@gmail.com" style="color: white; margin: 0 10px; text-decoration: none;">Contact Support</a>
    </div>

    <hr style="border: 0; border-top: 1px solid rgba(255,255,255,0.2); width: 50%; margin: 20px auto;">
    
    <p style="font-size: 0.9em; opacity: 0.7;">
        © 2025 StudyGrammarHub | Made with ❤️ for Students
    </p>
</footer>

    
