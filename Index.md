---
layout: default
title: Home
---

<style>
  /* Global Adjustments */
  body { margin: 0; padding: 0; background-color: #f8f9fa; font-family: 'Segoe UI', sans-serif; }

  /* Navigation Bar - Responsive */
  .nav-custom {
    display: flex;
    justify-content: space-around;
    background: #ffffff;
    padding: 12px;
    border-radius: 15px;
    margin: 10px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.05);
    position: sticky;
    top: 5px;
    z-index: 1000;
  }
  .nav-custom a { text-decoration: none; color: #2a5298; font-weight: 700; font-size: 0.9em; }

  /* Hero Section */
  .hero-section {
    background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%);
    color: white;
    padding: 50px 20px;
    text-align: center;
    border-radius: 0 0 30px 30px;
    margin-bottom: 20px;
    box-shadow: 0 10px 20px rgba(0,0,0,0.1);
  }
  .logo-img {
    width: 100px; height: 100px; 
    border-radius: 50%;
    margin-bottom: 15px;
    border: 3px solid rgba(255,255,255,0.8);
    background: white;
  }

  /* Section Headers */
  .section-title {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 25px 15px 10px;
  }
  .section-title h2 { font-size: 1.1rem; color: #1e3c72; margin: 0; border-left: 4px solid #ff8c00; padding-left: 10px; }
  .view-all { background: #e0f2fe; color: #0369a1; padding: 4px 10px; border-radius: 5px; text-decoration: none; font-size: 0.75rem; font-weight: bold; }

  /* Grid Layout (3 Items per row) */
  .grid-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 10px;
    padding: 0 15px;
  }
  .subject-box {
    background: #fff;
    border-radius: 15px;
    padding: 15px 5px;
    text-align: center;
    text-decoration: none;
    box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    border: 1px solid #f0f0f0;
  }
  .icon-circle {
    width: 45px; height: 45px;
    margin: 0 auto 8px;
    display: flex; align-items: center; justify-content: center;
    font-size: 22px; border-radius: 12px;
  }
  .subject-name { color: #333; font-size: 0.75rem; font-weight: 600; display: block; }

  /* Icon Colors */
  .bg-blue { background: #e0f2fe; color: #0369a1; }
  .bg-orange { background: #ffedd5; color: #c2410c; }
  .bg-purple { background: #f3e8ff; color: #7e22ce; }
  .bg-green { background: #dcfce7; color: #15803d; }
  .bg-red { background: #fee2e2; color: #b91c1c; }
  .bg-yellow { background: #fef9c3; color: #a16207; }

  /* Footer */
  .site-footer {
    background: #1e3c72;
    color: white;
    padding: 30px 20px;
    text-align: center;
    margin-top: 40px;
    border-radius: 30px 30px 0 0;
  }
</style>

<div class="nav-custom">
    <a href="./index.html">🏠 Home</a>
    <a href="./subjects.html">📚 Subjects</a>
    <a href="./about.html">🙋‍♂️ About</a>
</div>

<div class="hero-section">
    <img src="https://github.com/user-attachments/assets/54428106-4b55-46b7-8fa5-dc9a1774f7aa" alt="Logo" class="logo-img"> 
    <h1 style="font-size: 1.8em; margin: 0;">StudyGrammarHub</h1>
    <p style="font-size: 0.9em; opacity: 0.8;">Master Grammar, Unlock Success</p>
</div>

<div class="section-title">
  <h2>Grammar Lessons</h2>
  <a href="./subjects.html" class="view-all">See All</a>
</div>

<div class="grid-container">
  <a href="./tenses.html" class="subject-box">
    <div class="icon-circle bg-blue">📝</div>
    <span class="subject-name">Tenses</span>
  </a>
  <a href="./active-voice.html" class="subject-box">
    <div class="icon-circle bg-orange">🗣️</div>
    <span class="subject-name">Active Voice</span>
  </a>
  <a href="./articles.html" class="subject-box">
    <div class="icon-circle bg-purple">📖</div>
    <span class="subject-name">Articles</span>
  </a>
</div>

<div class="section-title">
  <h2>Study Material</h2>
  <a href="./materials.html" class="view-all">See All</a>
</div>

<div class="grid-container">
  <a href="./ncert.html" class="subject-box">
    <div class="icon-circle bg-green">📚</div>
    <span class="subject-name">NCERT</span>
  </a>
  <a href="./mindmaps.html" class="subject-box">
    <div class="icon-circle bg-red">💡</div>
    <span class="subject-name">Mind Maps</span>
  </a>
  <a href="./questions.html" class="subject-box">
    <div class="icon-circle bg-yellow">❓</div>
    <span class="subject-name">Important</span>
  </a>
</div>

<footer class="site-footer">
    <h3 style="margin: 0;">StudyGrammarHub</h3>
    <p style="font-size: 0.8em; opacity: 0.7; margin: 10px 0;">Quality Education for Everyone</p>
    <div style="margin: 15px 0;">
        <a href="./about.html" style="color: white; text-decoration: none; font-size: 0.8em;">About Us</a> | 
        <a href="mailto:contact@studygrammarhub.com" style="color: white; text-decoration: none; font-size: 0.8em;">Contact</a>
    </div>
    <p style="font-size: 0.7em; opacity: 0.5; margin-top: 20px;">© 2025 StudyGrammarHub</p>
</footer>
