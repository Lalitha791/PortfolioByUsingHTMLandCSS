# PortfolioByUsingHTMLandCSS
html and css understanding

https://github.com/Lalitha791/PortfolioByUsingHTMLandCSS/commit/7b0f0e9f31d677a48eae8cb47387da8a0255b357   #code html and css





🔹 Code Explanation

Basic Setup

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>


Declares HTML5 document.

Language = English.

meta charset="UTF-8" → supports all characters (emoji, symbols).

meta viewport → makes it responsive for mobile.

<title> → text shown in browser tab.

<link rel="stylesheet"> → connects CSS file.

Header (Navigation Bar)

<header>
  <div class="logo">MyLogo</div>
  <ul class="nav-links">
    <li><a href="#intro">Home</a></li>
    <li><a href="#skills">Skills</a></li>
    <li><a href="#projects">Projects</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</header>


header → fixed navigation bar.

.logo → brand/logo text.

.nav-links → list of navigation items.

<a href="#sectionID"> → jumps to page sections smoothly (because of CSS scroll-behavior: smooth).

Intro Section

<section id="intro" class="section">
  <h1>Hello, I'm <span>Lekhaa</span></h1>
  <p>Frontend Developer | Designer | Tech Enthusiast</p>
  <a href="#projects" class="btn">See My Work</a>
</section>


Main hero/intro area.

id="intro" links with nav.

<span> → highlights name with a different color (gold).

.btn → styled call-to-action button.

Skills Section

<section id="skills" class="section">
  <h2>My Skills</h2>
  <div class="skills-container">
    <div class="skill-card">HTML</div>
    <div class="skill-card">CSS</div>
    <div class="skill-card">JavaScript</div>
  </div>
</section>


Lists skills inside .skill-card.

Styled with hover effect (lift up card).

Projects Section

<section id="projects" class="section">
  <h2>Projects</h2>
  <div class="projects-container">
    <div class="project-card">
      <h3>Project 1</h3>
      <p>A cool web project description.</p>
    </div>
    <div class="project-card">
      <h3>Project 2</h3>
      <p>Another project I built.</p>
    </div>
  </div>
</section>


Showcases projects in .project-card boxes.

Hover: cards enlarge slightly with new background.

Contact Section

<section id="contact" class="section">
  <h2>Contact Me</h2>
  <p>Email me at <a href="mailto:example@email.com">example@email.com</a></p>
</section>


Provides contact info.

mailto: link → opens default email app when clicked.

Footer

<footer>
  <p>&copy; 2025 My Portfolio. All Rights Reserved.</p>
</footer>


Dark footer at the bottom with copyright.

✅ In short:
This HTML defines the structure of your portfolio website.

header = navigation

section = content blocks (intro, skills, projects, contact)

footer = ending note

Your CSS makes this structure look modern, animated, and interactive.



