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

<h2 style="text-align:center; margin-bottom: 30px;">Popular Subject Notes</h2>
<div class="subject-grid">
    
    <div class="subject-card">
        <img src="https://images.unsplash.com/photo-1456513080510-7bf3a84b82f8?w=400" alt="Grammar" style="width:100%;">
        <div style="padding: 20px; text-align: center;">
            <h3>English Grammar</h3>
            <p>Tense, Passive Voice, aur bahut kuch.</p>
            <a href="./grammar.md" style="background:#2a5298; color:white; padding:10px 20px; border-radius:5px; text-decoration:none; display:inline-block;">Notes Padhein</a>
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

    
