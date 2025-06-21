---
layout: default
title: Work Experience
---

<nav style="background-color: #222; padding: 10px; text-align: center; border-radius: 8px; margin-bottom: 30px;">
  <a href="/" style="text-decoration: none; margin: 0 15px; font-weight: bold; color: {% if page.title == 'Home' %}#8f0{% else %}white{% endif %};">Home</a>
  <a href="/work_experience" style="text-decoration: none; margin: 0 15px; font-weight: bold; color: {% if page.title == 'Work Experience' %}#8f0{% else %}white{% endif %};">Work Experience</a>
  <a href="/projects" style="text-decoration: none; margin: 0 15px; font-weight: bold; color: {% if page.title == 'Projects' %}#8f0{% else %}white{% endif %};">Projects</a>
  <a href="/resume" style="text-decoration: none; margin: 0 15px; font-weight: bold; color: {% if page.title == 'Resume' %}#8f0{% else %}white{% endif %};">Resume</a>
  <a href="/contact" style="text-decoration: none; margin: 0 15px; font-weight: bold; color: {% if page.title == 'Contact' %}#8f0{% else %}white{% endif %};">Contact</a>
</nav>



<div style="margin-bottom: 20px;">
<!--   <button onclick="this.nextElementSibling.style.display = this.nextElementSibling.style.display === 'none' ? 'block' : 'none';" style="background-color: transparent; border: 2px solid #8f0; color: #8f0; font-weight: bold; padding: 10px; width: 100%; text-align: left; border-radius: 8px; cursor: pointer;"> -->
    <button onclick="
    var content = this.nextElementSibling;
    var icon = this.querySelector('.icon');
    if (content.style.display === 'none') {
      content.style.display = 'block';
      icon.textContent = '∧';
    } else {
      content.style.display = 'none';
      icon.textContent = '∨';
    }
  " style="background-color: transparent; border: 2px solid #8f0; color: #8f0; font-weight: bold; padding: 10px; width: 100%; text-align: left; border-radius: 8px; cursor: pointer; display: flex; justify-content: space-between; align-items: center;">
    <div style="display: flex; flex-direction: column;">
      <span style="font-weight: bold; color: #8f0;">The University of Melbourne</span>
      <span style="font-weight: bold; color: white;">AI Research Fellow | Reporting to <a href="https://lars.kuliks.net/?page_id=6" style="color: #4fc3f7;">Prof Lars Kulik</a>, Jan 2023 – Present</span>
    </div>
      <span class="icon" style="font-size: 20px; margin-left: 10px;">∨</span>
  </button>
  <div style="display: none; margin-top: 10px; padding-left: 20px;">
    <ul>
      <li>Researcher for workstream 3 of the <a href="https://www.musicattunedcare.com/" style="color: #0bf;">MATCH project</a>.</li>
      <li>Development of machine learning models to automate the detection of agitation symptoms related to dementia.</li>
      <li>Designed and built the data engineering pipeline to extract and preprocess physiological data from Empatica's EmbracePlus wearable; this included architecting and managing a PostgreSQL database to store the aligned sensor and label data for analysis.</li>
      <li>Researched noise reduction techniques and integrated <a href="https://ieeexplore.ieee.org/document/9914782" style="color: #0bf;">DeepFilterNet</a> models into our data pipeline to remove/reduce noise from the collected audio data.</li>
      <li>Developed an <a href="https://github.com/stevcabello/CMAI-Labeller-App" style="color: #0bf;">Android/iOS app</a> for data collection of agitation symptoms in patients living with dementia.</li>
      <li>Supervised the development of the MATCH app, which integrates the Spotify API to provide music recommendations.</li>
<!--       <li>Supervised an undergraduate project (SCIE30001 - 2023 SEMESTER 1) titled "Music Genre Classification with ResNet and Bi-GRU Using Visual Spectrograms".</li> -->
      <li>Co-supervisor of 2 PhD students.</li>
      <li>Marker for Master of Information Technology theses during Semester 2, 2023 and Semester 1, 2024.</li>
      <li>Lecturer for Design of Algorithms (COMP20007) for Semester 1, 2024. Delivered lectures on String Matching, Dynamic Programming, Sorting Algorithms, Binary Search Trees, Hashing, and Data Compression.</li>
      <li>Reviewer for Conference on Information and Knowledge Management (CIKM) 2024.</li>
      <li>Reviewer for Knowledge Discovery in Databases (KDD) 2025 (<a href="https://kdd2025.kdd.org/research-track-program-committee/">link</a>).</li>
      <li>Technical representative of the MATCH Safety and Capacity Building Committees.</li>
    </ul>
  </div>
</div>

<div style="margin-bottom: 20px;">
<!--   <button onclick="this.nextElementSibling.style.display = this.nextElementSibling.style.display === 'none' ? 'block' : 'none';" style="background-color: transparent; border: 2px solid #8f0; color: #8f0; font-weight: bold; padding: 10px; width: 100%; text-align: left; border-radius: 8px; cursor: pointer;"> -->
  <button onclick="
    var content = this.nextElementSibling;
    var icon = this.querySelector('.icon');
    if (content.style.display === 'none') {
      content.style.display = 'block';
      icon.textContent = '∧';
    } else {
      content.style.display = 'none';
      icon.textContent = '∨';
    }
  " style="background-color: transparent; border: 2px solid #8f0; color: #8f0; font-weight: bold; padding: 10px; width: 100%; text-align: left; border-radius: 8px; cursor: pointer; display: flex; justify-content: space-between; align-items: center;">

    <div style="display: flex; flex-direction: column;">
      <span style="font-weight: bold; color: #8f0;">RMIT University</span>
      <span style="font-weight: bold; color: white;">Academic Tutor | Reporting to <a href="https://www.rmit.edu.au/contact/staff-contacts/academic-staff/n/naghizade-dr-e" style="color: #4fc3f7;">Dr Elham Naghizade</a>, Jul 2023 – Present</span>
    </div>
    <span class="icon" style="font-size: 20px; margin-left: 10px;">∨</span>
  </button>
  <div style="display: none; margin-top: 10px; padding-left: 20px;">
    <ul>
      <li>Tutor, Lab Demonstrator, and Marker for <strong>Algorithms and Analysis (COSC2123/COSC1285)</strong>.</li>
      <li>Explain key algorithmic design paradigms: brute force, divide and conquer, decrease and conquer, transform and conquer, greedy, dynamic programming and iterative improvement.</li>
      <li>Explain key data structures: trees, lists, stacks, queues, hash tables and graph representations.</li>
      <li>Theoretically compare and analyse the time complexities of algorithms and data structures.</li>
    </ul>
  </div>
</div>

<div style="margin-bottom: 20px;">
<!--   <button onclick="this.nextElementSibling.style.display = this.nextElementSibling.style.display === 'none' ? 'block' : 'none';" style="background-color: transparent; border: 2px solid #8f0; color: #8f0; font-weight: bold; padding: 10px; width: 100%; text-align: left; border-radius: 8px; cursor: pointer;"> -->
  <button onclick="
    var content = this.nextElementSibling;
    var icon = this.querySelector('.icon');
    if (content.style.display === 'none') {
      content.style.display = 'block';
      icon.textContent = '∧';
    } else {
      content.style.display = 'none';
      icon.textContent = '∨';
    }
  " style="background-color: transparent; border: 2px solid #8f0; color: #8f0; font-weight: bold; padding: 10px; width: 100%; text-align: left; border-radius: 8px; cursor: pointer; display: flex; justify-content: space-between; align-items: center;">

    <div style="display: flex; flex-direction: column;">
      <span style="font-weight: bold; color: #8f0;">RMIT University</span>
      <span style="font-weight: bold; color: white;">Research Assistant | Reported to <a href="https://www.rmit.edu.au/contact/staff-contacts/academic-staff/n/naghizade-dr-e" style="color: #4fc3f7;">Dr Elham Naghizade</a>, Nov 2022 – Apr 2023</span>
    </div>
    <span class="icon" style="font-size: 20px; margin-left: 10px;">∨</span>
  </button>
  <div style="display: none; margin-top: 10px; padding-left: 20px;">
    <ul>
      <li>Developed <a href="https://github.com/stevcabello/RMIT-ABC-Fact-Checked-Data-Collection" style="color: #0bf;">scripts</a> for web scraping ABC's Fact Check website to identify news with tweet/twitter-related content.</li>
      <li>Developed scripts to use Twitter API to find the source (i.e., original tweet) from each tweet extracted from "The Claim" section on ABC's Fact Check website.</li>
      <li>Built scripts to use Twitter API and generate cascades from tweets related to anti-feminist political discourse in Iran.</li>
      <li>Explored the ChatGPT API to automate the identification of sexism in tweets.</li>
      <li>Delivered a talk: "ChatGPT as a scripting tool for researchers" to CHAI Human Information REtrieval (CHIRE) group at RMIT. I explained how to use ChatGPT for data processing and modelling purposes.</li>
    </ul>
  </div>
</div>

<div style="margin-bottom: 20px;">
<!--   <button onclick="this.nextElementSibling.style.display = this.nextElementSibling.style.display === 'none' ? 'block' : 'none';" style="background-color: transparent; border: 2px solid #8f0; color: #8f0; font-weight: bold; padding: 10px; width: 100%; text-align: left; border-radius: 8px; cursor: pointer;"> -->
    <button onclick="
    var content = this.nextElementSibling;
    var icon = this.querySelector('.icon');
    if (content.style.display === 'none') {
      content.style.display = 'block';
      icon.textContent = '∧';
    } else {
      content.style.display = 'none';
      icon.textContent = '∨';
    }
  " style="background-color: transparent; border: 2px solid #8f0; color: #8f0; font-weight: bold; padding: 10px; width: 100%; text-align: left; border-radius: 8px; cursor: pointer; display: flex; justify-content: space-between; align-items: center;">

    <div style="display: flex; flex-direction: column;">
      <span style="font-weight: bold; color: #8f0;">Rosetta Analytics</span>
      <span style="font-weight: bold; color: white;">Senior Software Engineer | Reported to <a href="https://anthonyquattrone.com/" style="color: #4fc3f7;">Dr Anthony Quattrone</a>, Nov 2021 – Nov 2022</span>
    </div>
    <span class="icon" style="font-size: 20px; margin-left: 10px;">∨</span>
  </button>
  <div style="display: none; margin-top: 10px; padding-left: 20px;">
    <ul>
      <li>Understood requirements of current and prospective clients.</li>
      <li>Provided support for the Regulatory Information Notice (RIN) clients.</li>
      <li>Implemented new features for RIN portals using PHP, JavaScript and MySQL.</li>
      <li>Developed and supported mapping portals using JavaScript, Google Maps and GIS technologies.</li>
      <li>Optimised database operations.</li>
      <li>Managed Amazon EC2 servers.</li>
    </ul>
  </div>
</div>

<div style="margin-bottom: 20px;">
<!--   <button onclick="this.nextElementSibling.style.display = this.nextElementSibling.style.display === 'none' ? 'block' : 'none';" style="background-color: transparent; border: 2px solid #8f0; color: #8f0; font-weight: bold; padding: 10px; width: 100%; text-align: left; border-radius: 8px; cursor: pointer;"> -->
    <button onclick="
    var content = this.nextElementSibling;
    var icon = this.querySelector('.icon');
    if (content.style.display === 'none') {
      content.style.display = 'block';
      icon.textContent = '∧';
    } else {
      content.style.display = 'none';
      icon.textContent = '∨';
    }
  " style="background-color: transparent; border: 2px solid #8f0; color: #8f0; font-weight: bold; padding: 10px; width: 100%; text-align: left; border-radius: 8px; cursor: pointer; display: flex; justify-content: space-between; align-items: center;">

    <div style="display: flex; flex-direction: column;">
      <span style="font-weight: bold; color: #8f0;">RMIT University</span>
      <span style="font-weight: bold; color: white;">Academic Mentor | Reporting to <a href="https://www.rmit.edu.au/contact/staff-contacts/academic-staff/c/cavedon-professor-lawrence" style="color: #4fc3f7;">Prof Lawrence Cavedon</a>, Aug 2021 – Nov 2021</span>
    </div>
  <span class="icon" style="font-size: 20px; margin-left: 10px;">∨</span>
  </button>
  <div style="display: none; margin-top: 10px; padding-left: 20px;">
    <ul>
      <li>Mentored machine learning projects for Masters students working with industry partners (Data Science Postgraduate Program).</li>
      <li>Provided technical advice and evaluated final reports.</li>
    </ul>
  </div>
</div>

<div style="margin-bottom: 20px;">
<!--   <button onclick="this.nextElementSibling.style.display = this.nextElementSibling.style.display === 'none' ? 'block' : 'none';" style="background-color: transparent; border: 2px solid #8f0; color: #8f0; font-weight: bold; padding: 10px; width: 100%; text-align: left; border-radius: 8px; cursor: pointer;"> -->
    <button onclick="
    var content = this.nextElementSibling;
    var icon = this.querySelector('.icon');
    if (content.style.display === 'none') {
      content.style.display = 'block';
      icon.textContent = '∧';
    } else {
      content.style.display = 'none';
      icon.textContent = '∨';
    }
  " style="background-color: transparent; border: 2px solid #8f0; color: #8f0; font-weight: bold; padding: 10px; width: 100%; text-align: left; border-radius: 8px; cursor: pointer; display: flex; justify-content: space-between; align-items: center;">

    <div style="display: flex; flex-direction: column;">
      <span style="font-weight: bold; color: #8f0;">ESPOL / Universidad de Guayaquil</span>
      <span style="font-weight: bold; color: white;">Lecturer, May 2017 – Dec 2017</span>
    </div>
    <span class="icon" style="font-size: 20px; margin-left: 10px;">∨</span>
  </button>
  <div style="display: none; margin-top: 10px; padding-left: 20px;">
    <ul>
      <li>Lectured in several courses: Operating Systems, Object-Oriented Software Engineering, Compilers, Data Structures, Databases, Fundamentals of Programming (Python) and Object-Oriented Programming (Java).</li>
      <li>Directed a community-focused project related to the development of computational thinking in children through the use of programmable technologies.</li>
    </ul>
  </div>
</div>

<div style="margin-bottom: 20px;">
<!--   <button onclick="this.nextElementSibling.style.display = this.nextElementSibling.style.display === 'none' ? 'block' : 'none';" style="background-color: transparent; border: 2px solid #8f0; color: #8f0; font-weight: bold; padding: 10px; width: 100%; text-align: left; border-radius: 8px; cursor: pointer;"> -->
    <button onclick="
    var content = this.nextElementSibling;
    var icon = this.querySelector('.icon');
    if (content.style.display === 'none') {
      content.style.display = 'block';
      icon.textContent = '∧';
    } else {
      content.style.display = 'none';
      icon.textContent = '∨';
    }
  " style="background-color: transparent; border: 2px solid #8f0; color: #8f0; font-weight: bold; padding: 10px; width: 100%; text-align: left; border-radius: 8px; cursor: pointer; display: flex; justify-content: space-between; align-items: center;">

    <div style="display: flex; flex-direction: column;">
      <span style="font-weight: bold; color: #8f0;">Carro Seguro S.A.</span>
      <span style="font-weight: bold; color: white;">Software Developer, Feb 2013 – Feb 2015</span>
    </div>
    <span class="icon" style="font-size: 20px; margin-left: 10px;">∨</span>
  </button>
  <div style="display: none; margin-top: 10px; padding-left: 20px;">
    <ul>
      <li>Supported and developed web platforms using ASP.NET and SQL technologies.</li>
      <li>Deployed <a href="https://play.google.com/store/apps/details?id=com.devsu.cervezasmart&pli=1" style="color: #0bf;">Android applications</a> with REST and SOAP web services.</li>
      <li>Implemented an HTTP Servlet for image transfer.</li>
      <li>Configured Linux servers.</li>
    </ul>
  </div>
</div>

<div style="margin-bottom: 20px;">
<!--   <button onclick="this.nextElementSibling.style.display = this.nextElementSibling.style.display === 'none' ? 'block' : 'none';" style="background-color: transparent; border: 2px solid #8f0; color: #8f0; font-weight: bold; padding: 10px; width: 100%; text-align: left; border-radius: 8px; cursor: pointer;"> -->
    <button onclick="
    var content = this.nextElementSibling;
    var icon = this.querySelector('.icon');
    if (content.style.display === 'none') {
      content.style.display = 'block';
      icon.textContent = '∧';
    } else {
      content.style.display = 'none';
      icon.textContent = '∨';
    }
  " style="background-color: transparent; border: 2px solid #8f0; color: #8f0; font-weight: bold; padding: 10px; width: 100%; text-align: left; border-radius: 8px; cursor: pointer; display: flex; justify-content: space-between; align-items: center;">

    <div style="display: flex; flex-direction: column;">
      <span style="font-weight: bold; color: #8f0;">Carro Seguro S.A.</span>
      <span style="font-weight: bold; color: white;">Technical Support Engineer, Jun 2009 – Feb 2013</span>
    </div>
    <span class="icon" style="font-size: 20px; margin-left: 10px;">∨</span>
  </button>
  <div style="display: none; margin-top: 10px; padding-left: 20px;">
    <ul>
      <li>Supervised the correct operation of 130 monitoring towers nationwide.</li>
      <li>Tested, configured, and installed GPRS equipment.</li>
      <li>Repaired Motorola radios and provided maintenance.</li>
      <li>Configured VHF and UHF radios.</li>
    </ul>
  </div>
</div>

    
---
