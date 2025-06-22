---
layout: default
title: My Portfolio
---

# Welcome to My Portfolio

## My Projects

### Find the Number

<div style="display: flex; align-items: center; gap: 20px; margin-bottom: 40px;">
  <div style="flex: 1;">
    <p>A number-finding game built in Python using Pygame. It includes multiple rounds, interactive line drawing, sound feedback, and game logic that ends on incorrect selections.</p>
    <p>
      <button onclick="document.getElementById('demo1').style.display='block'">Demo</button>
      <div id="demo1" style="display:none;">
        <video width="100%" height="auto" controls>
          <source src="FindNumberDemo.mov" type="video/mp4">
          Your browser does not support the video tag.
        </video>
      </div>

      <a href="https://github.com/yourusername/hangman" target="_blank"><button>Code</button></a>
    </p>
  </div>
  <img src="FindNumber.png" alt="Find the Number Game" width="300" style="border-radius: 10px;">
</div>

---

### Connect the Dots

<div style="display: flex; align-items: center; gap: 20px; margin-bottom: 40px;">
  <div style="flex: 1;">
    <p>An interactive game where players take turns drawing lines to complete squares. Built in Kivy, this project highlights turn-based gameplay, dynamic UI updates, and scoring logic.</p>
    <p>
      <button onclick="document.getElementById('demo2').style.display='block'">Demo</button>
      <div id="demo2" style="display:none;">
        <video width="100%" height="auto" controls>
          <source src="demoVideo.mp4" type="video/mp4">
          Your browser does not support the video tag.
        </video>
      </div>
      <a href="https://github.com/yourusername/connect-the-dots" target="_blank"><button>Code</button></a>
    </p>
  </div>
  <img src="connectTheDots.jpeg" alt="Connect the Dots Game" width="300" style="border-radius: 10px;">
</div>

---

## About Me (click to show/hide)

<details>
  <summary style="cursor: pointer;">Click to expand</summary>
  <p>
    I am a Montessori educator turned software engineer passionate about purpose-driven tech. I bring empathy, rapid learning, and creativity into every line of code. With a strong background in Python, AI, and frontend development, I create tools that solve real problems and inspire curiosity.
  </p>
</details>
