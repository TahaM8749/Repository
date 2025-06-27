---
layout: default
title: My Portfolio
---

# Welcome to My Portfolio

## My Projects


<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px;">

  <!-- Project Card -->
  <div style="border: 1px solid #ccc; border-radius: 10px; padding: 16px;">
       <h3>Find the Number </h3>
    <img src="FindNumber.png" alt="Find the Number Game" style="width: 100%; border-radius: 10px;">
        <p>A number-finding game built in Python using Pygame. It includes multiple rounds, interactive line drawing, sound feedback, and game logic that ends on incorrect selections.</p>
        <p>
          <button onclick="document.getElementById('demo9').style.display='block'">Demo</button>
         </p> 
          <div id="demo9" style="display:none;">
            <video width="100%" height="auto" controls muted autoplay>
              <source src="FindNumberDemo.mov" type="video/mp4">
              Your browser does not support the video tag.
            </video>
  </div>  
    <div style="margin-top: 8px;">
      <span style="background: #f2dede; padding: 4px 8px; border-radius: 6px;">Python</span>
      <span style="background: #d9edf7; padding: 4px 8px; border-radius: 6px;">Game Design</span>
      <span style="background: #dff0d8; padding: 4px 8px; border-radius: 6px;">Pygame</span>
    </div>
  </div>

  <!-- Another Project Card -->
  <div style="border: 1px solid #ccc; border-radius: 10px; padding: 16px;">
    
        <h3>✈️ Travel Reminder</h3>
        <img src="TravelReminder.png" alt="Travel Reminder" width="300" style="border-radius: 10px;">
          <p>An intelligent travel assistant built using <strong>n8n</strong>, this project automates the task of reminding travelers about their upcoming trips and enriches the experience with destination-specific suggestions. The workflow checks travel dates from stored documents, identifies travelers with an upcoming trip, and automatically sends a personalized email reminder a day before departure.</p>
          <p>The system is:</p>
          <ul>
            <li><strong>Efficient</strong>: Automatically parses and processes travel data daily.</li>
            <li><strong>Smart</strong>: Matches travel destinations with curated local recommendations.</li>
            <li><strong>Reliable</strong>: Uses n8n’s powerful scheduling and automation.</li>
            <li><strong>Scalable</strong>: Easily extendable to include weather forecasts and local events.</li>
          </ul>
          <p>
            <button onclick="document.getElementById('demo8').style.display='block'">Demo</button>
          </p>
          <div id="demo8" style="display:none;">
              <video width="100%" height="auto" controls muted autoplay>
                <source src="DemoTravelReminder.mov" type="video/mp4">
                Your browser does not support the video tag.
              </video>
        
    </div>
    <div style="margin-top: 8px;">
      <span style="background: #fcf8e3; padding: 4px 8px; border-radius: 6px;">n8n</span>
      <span style="background: #d9edf7; padding: 4px 8px; border-radius: 6px;">Automation</span>
      <span style="background: #f5f5f5; padding: 4px 8px; border-radius: 6px;">Node.js</span>
     
     
    </div>
  </div>


<!-- Another Project Card -->
  <div style="border: 1px solid #ccc; border-radius: 10px; padding: 16px;">
        <h3>📝 Word Builder Challenge</h3>
        <img src="GenWords.png" alt="Gen Words" width="300" style="border-radius: 10px;">
          <p>
            A one-minute word game where players build valid words using only the letters from a long given word. Includes live word validation and scoring. Built in Python with a focus on string handling, timers, and dictionary APIs.
       </p>
          <p>
            <button onclick="document.getElementById('demo7').style.display='block'">Demo</button>
          </p>
          <div id="demo7" style="display:none;">
            <video width="100%" height="auto" controls muted autoplay>
              <source src="DemoGenWords.mov" type="video/mp4">
              Your browser does not support the video tag.
            </video>
        
    </div>
    <div style="margin-top: 8px;">
      <span style="background: #fcf8e3; padding: 4px 8px; border-radius: 6px;">Python</span>
      <span style="background: #d9edf7; padding: 4px 8px; border-radius: 6px;">Kivy</span>
      <span style="background: #dff0d8; padding: 4px 8px; border-radius: 6px;">Game Design</span>
    </div>
  </div>

 <!-- Project Card -->
  <div style="border: 1px solid #ccc; border-radius: 10px; padding: 16px;">
    <h3>🔤 Hangman </h3>
    <img src="hangman.png" alt="Find the Number Game" style="width: 100%; border-radius: 10px;">
    
    <p>
      A simple word-guessing game built with Python and Pygame. Players guess letters to uncover a hidden word before the hangman is fully drawn. Features include random word selection, visual feedback, and mouse-based letter interaction.:</p>
    <p>
      <button onclick="document.getElementById('demo10').style.display='block'">Demo</button>
    </p>
    <div id="demo10" style="display:none;">
      <video width="100%" height="auto" controls muted autoplay>
        <source src="hangman.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </div>
    
    
    <div style="margin-top: 8px;">
      <span style="background: #f2dede; padding: 4px 8px; border-radius: 6px;">Python</span>
      <span style="background: #d9edf7; padding: 4px 8px; border-radius: 6px;">Game Design</span>
      <span style="background: #dff0d8; padding: 4px 8px; border-radius: 6px;">Pygame</span>
    </div>
  </div>

  <!-- Another Project Card -->
  <div style="border: 1px solid #ccc; border-radius: 10px; padding: 16px;">
   
    <h3>🧠 20 Questions Game</h3>
     <img src="20Questions.png" alt="Travel Reminder" style="width: 100%; border-radius: 10px;">
     <p>
      A classic interactive guessing game where the human beings tries to determine what the computer is thinking of by asking a series of yes/no questions. The goal is for the human beings to guess the correct object, person, or concept in 20 questions or fewer. </p>
    <p>
      <button onclick="document.getElementById('demo11').style.display='block'">Demo</button>
    </p>
    <div id="demo11" style="display:none;">
      <video width="100%" height="auto" controls muted autoplay>
        <source src="Demo20Questions.mov" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </div>
    <div style="margin-top: 8px;">
      <span style="background: #fcf8e3; padding: 4px 8px; border-radius: 6px;">Kivy</span>
      <span style="background: #d9edf7; padding: 4px 8px; border-radius: 6px;">AI</span>
      <span style="background: #f5f5f5; padding: 4px 8px; border-radius: 6px;">Game Design</span>
       <span style="background:  #e6e6fa; padding: 4px 8px; border-radius: 6px;">Python</span>
    </div>
  </div>

 <!-- Another Project Card -->
  <div style="border: 1px solid #ccc; border-radius: 10px; padding: 16px;">
   
    <h3>🧠 Connect the Dotse</h3>
     <img src="connectTheDots.jpeg" alt="Travel Reminder" style="width: 100%; border-radius: 10px;">
     <p>An interactive game where players take turns drawing lines to complete squares. Built in Kivy, this project highlights turn-based gameplay, dynamic UI updates, and scoring logic.</p>
    <p>
      <button onclick="document.getElementById('demo12').style.display='block'">Demo</button>
    </p>
      <div id="demo12" style="display:none;">
        <video width="100%" height="auto" controls muted autoplay>
          <source src="demoVideo.mp4" type="video/mp4">
          Your browser does not support the video tag.
        </video>
      </div>
    <div style="margin-top: 8px;">
      <span style="background: #fcf8e3; padding: 4px 8px; border-radius: 6px;">Game Design</span>
      <span style="background: #d9edf7; padding: 4px 8px; border-radius: 6px;">Kivy</span>
      <span style="background: #f5f5f5; padding: 4px 8px; border-radius: 6px;">Python</span>
    </div>
  </div>

</div>


<!-- Another Project Card -->
  <div style="border: 1px solid #ccc; border-radius: 10px; padding: 16px;">
   
    <h3>Montessori Lessons Recommender</h3>
     <img src="MontessoriLessons.png" alt="Montessori Lessons flowchart" style="width: 100%; border-radius: 10px;">
     <p>A full-stack web application that helps Montessori educators recommend age-appropriate lessons for children based on their learning history. Built with Flask (Python) and SQLite for the backend and vanilla JavaScript/HTML/CSS for the frontend, the app features: </p>

     <ul>
            <li>A dynamic form to input child details and mastered lessons.</li>
            <li>Real-time lesson name suggestions with autocomplete</li>
            <li>Automatic recommendation of the next appropriate lesson</li>
            <li><Visual breakdown of mastered vs. unmastered lessons</li>
            <li>Integrated Montessori lesson flowchart for reference</li>
          </ul>

<p>This tool streamlines lesson planning and supports personalized learning paths in Montessori classrooms.</p>
    <p>
      <button onclick="document.getElementById('demo1').style.display='block'">Demo</button>
    </p>
      <div id="demo1" style="display:none;">
        <video width="100%" height="auto" controls muted autoplay>
          <source src="MontessoriLessonsDemo.mov" type="video/mp4">
          Your browser does not support the video tag.
        </video>
      </div>
    <div style="margin-top: 8px;">
      <span style="background: #fcf8e3; padding: 4px 8px; border-radius: 6px;">Game Design</span>
      <span style="background: #d9edf7; padding: 4px 8px; border-radius: 6px;">Kivy</span>
      <span style="background: #f5f5f5; padding: 4px 8px; border-radius: 6px;">Python</span>
    </div>
  </div>

</div>


## About Me 

<p>
  <button onclick="document.getElementById('demo7').style.display='block'">Resume</button>
</p>


<p>
  I am a Montessori educator turned software engineer passionate about purpose-driven tech. I bring empathy, rapid learning, and creativity into every line of code. With a strong background in Python, AI, and frontend development, I create tools that solve real problems and inspire curiosity.
</p>

<div style="display: flex; justify-content: space-around; text-align: center; margin-top: 20px;">
  <div>
    <h4>Enrichment Initiative</h4>
    <p style="font-size: 24px; font-weight: bold;">75%</p>
  </div>
  <div>
    <h4>Growth in Key Metrics</h4>
    <p style="font-size: 24px; font-weight: bold;">80%</p>
  </div>
  <div>
    <h4>Team Collaboration</h4>
    <p style="font-size: 24px; font-weight: bold;">90%</p>
  </div>
</div>




