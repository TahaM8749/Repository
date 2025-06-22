---
layout: default
title: My Portfolio
---

# Welcome to My Portfolio

<p>
  <button onclick="showBox('box1')">Show Projects</button>
  <button onclick="showBox('box2')">Show About Me</button>
  <button onclick="showBox('box3')">Show Demo</button>
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

<script>
  function showBox(boxId) {
  const boxes = ['box1', 'box2', 'box3'];
  boxes.forEach(id => {
    document.getElementById(id).style.display = (id === boxId) ? 'block' : 'none';
    });
  }
</script>

