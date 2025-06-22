---
layout: default
title: My Portfolio
---

# Welcome to My Portfolio

<p>
  <button onclick="document.getElementById('box1').style.display='block'; document.getElementById('box2').style.display='none';     
          document.getElementById('box3').style.display='none';">
          Show Projects
  </button>
  
  <button onclick="document.getElementById('box2').style.display='block'; document.getElementById('box1').style.display='none';     
          document.getElementById('box3').style.display='none';">
          Show About Me
  </button>
  
  <button onclick="document.getElementById('box3').style.display='block'; document.getElementById('box1').style.display='none';     
          document.getElementById('box2').style.display='none';">
          Show Demo
  </button>
</p>

<div id="box1" style="display:none;">
  <h2>Projects</h2>
  <ul>
    <li>AI Chatbot</li>
    <li>Educational App</li>
    <li>Game in Python</li>
  </ul>
</div>

<div id="box2" style="display:none;">
  <h2>About Me</h2>
  <p>I am a Montessori educator turned software engineer passionate about purpose-driven tech.</p>
</div>



