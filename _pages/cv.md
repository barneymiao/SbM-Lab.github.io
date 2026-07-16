---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---


{% include base_path %}

<div class="cv-download-links" style="margin-bottom: 30px;">
  <a href="{{ base_path }}/files/cv.pdf" class="btn btn--primary" style="background-color: #003B5C; border-color: #003B5C;">Download CV as PDF</a>
  <a href="{{ base_path }}/cv/" class="btn btn--inverse">View Markdown CV</a>
</div>

<style>
  /* Clean Minimalist Timeline */
  .education-timeline {
    position: relative;
    margin: 30px 0 30px 15px;
    padding: 0;
    list-style: none;
    border-left: 2px solid #003B5C; /* Matches your UCalgary blue */
  }

  .education-timeline-item {
    position: relative;
    margin-bottom: 25px;
    padding-left: 25px;
  }

  /* Timeline Dot */
  .education-timeline-item::before {
    content: '';
    position: absolute;
    left: -7px;
    top: 6px;
    width: 12px;
    height: 12px;
    border-radius: 50%;
    background: #003B5C;
    border: 2px solid #fff;
    box-shadow: 0 0 0 2px #003B5C;
  }

  .edu-year {
    font-weight: 700;
    color: #003B5C;
    font-size: 1.05em;
    margin-bottom: 2px;
  }

  .edu-degree {
    font-weight: 600;
    font-size: 1.15em;
    margin: 0 0 3px 0;
    color: #333;
  }

  .edu-inst {
    font-size: 0.95em;
    color: #666;
    margin: 0;
  }

  .edu-details {
    font-size: 0.9em;
    color: #555;
    margin-top: 4px;
    font-style: italic;
  }
</style>

Education
======

<ul class="education-timeline">
  
  <li class="education-timeline-item">
    <div class="edu-year">April 2023 - June 2026</div>
    <div class="edu-degree">Ph.D. in Civil and Environmental Engineering</div>
    <div class="edu-inst">Stanford University</div>
    <div class="edu-details">
      Minor in Computer Science <br>
      Advisor: Michael D. Lepech
    </div>
  </li>

  <li class="education-timeline-item">
    <div class="edu-year"> September 2021 - April 2023</div>
    <div class="edu-degree">M.S. in Structural Engineering</div>
    <div class="edu-inst">Stanford University</div>
  </li>

  <li class="education-timeline-item">
    <div class="edu-year">September 2017 - May 2021</div>
    <div class="edu-degree">B.Sc. in Civil Engineering</div>
    <div class="edu-inst">University of Calgary</div>
    <div class="edu-details">Minor in Structural Engineering</div>
  </li>

</ul>

Work Experience
======

<style>
  /* Work Experience Timeline */
  .experience-timeline {
    position: relative;
    margin: 30px 0 30px 15px;
    padding: 0;
    list-style: none;
    border-left: 2px solid #003B5C; /* Matching UCalgary Blue */
  }

  .experience-timeline-item {
    position: relative;
    margin-bottom: 25px;
    padding-left: 25px;
  }

  /* Timeline Dot */
  .experience-timeline-item::before {
    content: '';
    position: absolute;
    left: -7px;
    top: 6px;
    width: 12px;
    height: 12px;
    border-radius: 50%;
    background: #003B5C;
    border: 2px solid #fff;
    box-shadow: 0 0 0 2px #003B5C;
  }

  .exp-date {
    font-weight: 700;
    color: #003B5C;
    font-size: 1.05em;
    margin-bottom: 2px;
    text-transform: uppercase;
    letter-spacing: 0.5px;
  }

  .exp-title {
    font-weight: 600;
    font-size: 1.15em;
    margin: 0 0 3px 0;
    color: #333;
  }

  .exp-inst {
    font-size: 0.95em;
    color: #555;
    margin: 0;
    font-weight: 500;
  }

  .exp-dept {
    font-size: 0.9em;
    color: #666;
    margin-top: 2px;
    font-style: italic;
  }
</style>

<ul class="experience-timeline">

  <li class="experience-timeline-item">
    <div class="exp-date">Aug 2026 – Present</div>
    <div class="exp-title">Assistant Professor</div>
    <div class="exp-inst">University of Calgary</div>
    <div class="exp-dept">Department of Civil Engineering</div>
  </li>

  <li class="experience-timeline-item">
    <div class="exp-date">2021 – 2026</div>
    <div class="exp-title">Graduate Student Researcher</div>
    <div class="exp-inst">Stanford University</div>
    <div class="exp-dept">
      Department of Civil and Environmental Engineering <br>
      Advisor: Michael D. Lepech
    </div>
  </li>

  <li class="experience-timeline-item">
    <div class="exp-date">2020 – 2021</div>
    <div class="exp-title">Undergraduate Student Researcher</div>
    <div class="exp-inst">University of Calgary</div>
    <div class="exp-dept">
      Department of Civil Engineering <br>
      Advisor: [Advisor Name]
    </div>
  </li>

</ul>
  
Service & Leadership
======

<style>
  .service-category {
    margin-top: 20px;
    margin-bottom: 15px;
  }
  
  .service-title {
    font-weight: 600;
    font-size: 1.2em;
    color: #333;
    margin-bottom: 8px;
    border-bottom: 1px solid #ddd;
    padding-bottom: 4px;
  }

  .service-list {
    list-style: none;
    padding-left: 0;
    margin: 0;
  }

  .service-item {
    position: relative;
    padding-left: 20px;
    margin-bottom: 8px;
    font-size: 1.0em;
    color: #444;
  }

  /* Custom clean bullet to match the blue accents */
  .service-item::before {
    content: "•";
    color: #003B5C;
    font-weight: bold;
    font-size: 1.2em;
    position: absolute;
    left: 3px;
    top: -2px;
  }

  .if-badge {
    font-weight: 600;
    color: #003B5C;
    font-size: 0.9em;
  }
</style>

Awards & Scholarships
======

<style>
  .awards-subheading {
    font-weight: 600;
    font-size: 1.25em;
    color: #333;
    margin-top: 25px;
    margin-bottom: 12px;
    border-bottom: 1px solid #ddd;
    padding-bottom: 4px;
  }

  .awards-list {
    list-style: none;
    padding-left: 0;
    margin: 15px 0;
  }

  .award-item {
    position: relative;
    padding-left: 25px;
    margin-bottom: 15px;
    line-height: 1.4;
  }

  /* Award Symbol */
  .award-item.trophy::before {
    content: "🏆";
    font-size: 0.95em;
    position: absolute;
    left: 0;
    top: 1px;
  }

  /* Scholarship Symbol */
  .award-item.scholarship::before {
    content: "🎓";
    font-size: 0.95em;
    position: absolute;
    left: 0;
    top: 1px;
  }

  .award-year {
    font-weight: 700;
    color: #003B5C; /* Calgary Blue */
    display: inline-block;
    width: 50px;
  }

  .award-details {
    display: inline;
    color: #333;
  }

  .award-title {
    font-weight: 600;
  }

  .award-org {
    color: #666;
    font-style: italic;
  }
</style>

<div class="awards-subheading">Awards & Fellowships</div>
<ul class="awards-list">

  <li class="award-item trophy">
    <span class="award-year">2026</span>
    <span class="award-details">
      <span class="award-title">Craig F. Bohren Best Student Presentation Award (1st Place)</span>, 
      <span class="award-org">SPIE Smart Structures + Nondestructive Evaluation</span>
    </span>
  </li>

  <li class="award-item trophy">
    <span class="award-year">2024</span>
    <span class="award-details">
      <span class="award-title">Best Poster Award</span>, 
      <span class="award-org">Stanford Doerr School of Sustainability Research Review</span>
    </span>
  </li>

  <li class="award-item trophy">
    <span class="award-year">2024</span>
    <span class="award-details">
      <span class="award-title">Leavell Fellowship on Sustainable Built Environment</span>, 
      <span class="award-org">Stanford Department of Civil and Environmental Engineering</span>
    </span>
  </li>

  <li class="award-item trophy">
    <span class="award-year">2022</span>
    <span class="award-details">
      <span class="award-title">Best Poster (Runner-Up)</span>, 
      <span class="award-org">9th ACM International Conference for Energy Efficient Buildings, Cities, and Transportation (BuildSys '22)</span>
    </span>
  </li>

  <li class="award-item trophy">
    <span class="award-year">2021</span>
    <span class="award-details">
      <span class="award-title">School of Engineering Graduate Fellowship</span>, 
      <span class="award-org">Stanford Department of Civil & Environmental Engineering</span>
    </span>
  </li>

  <li class="award-item trophy">
    <span class="award-year">2020</span>
    <span class="award-details">
      <span class="award-title">NSERC Research Award</span>, 
      <span class="award-org">Natural Sciences and Engineering Research Council of Canada (NSERC)</span>
    </span>
  </li>

</ul>

<div class="awards-subheading">Scholarships</div>
<ul class="awards-list">

  <li class="award-item scholarship">
    <span class="award-year">2020</span>
    <span class="award-details">
      <span class="award-title">Louise McKinney Scholarship</span>, 
      <span class="award-org">Government of Alberta</span>
    </span>
  </li>

  <li class="award-item scholarship">
    <span class="award-year">2020</span>
    <span class="award-details">
      <span class="award-title">Alex Bakshan Memorial Scholarship</span>, 
      <span class="award-org">Alberta Chapter of the American Concrete Institute (ACI)</span>
    </span>
  </li>

  <li class="award-item scholarship">
    <span class="award-year">2020</span>
    <span class="award-details">
      <span class="award-title">Japex/Jacos Scholarship in Engineering</span>, 
      <span class="award-org">Japex</span>
    </span>
  </li>

  <li class="award-item scholarship">
    <span class="award-year">2019</span>
    <span class="award-details">
      <span class="award-title">Calgary Construction Association (CCA) Member's Scholarship</span>, 
      <span class="award-org">Calgary Construction Association (CCA)</span>
    </span>
  </li>

  <li class="award-item scholarship">
    <span class="award-year">2019</span>
    <span class="award-details">
      <span class="award-title">Canadian Society for Civil Engineering Scholarship</span>, 
      <span class="award-org">Canadian Society for Civil Engineering (Calgary Section)</span>
    </span>
  </li>

  <li class="award-item scholarship">
    <span class="award-year">2018</span>
    <span class="award-details">
      <span class="award-title">TransAlta Corporation Memorial Scholarship</span>, 
      <span class="award-org">TransAlta</span>
    </span>
  </li>

  <li class="award-item scholarship">
    <span class="award-year">2018</span>
    <span class="award-details">
      <span class="award-title">Jason Lang Scholarship</span>, 
      <span class="award-org">Government of Alberta</span>
    </span>
  </li>

  <li class="award-item scholarship">
    <span class="award-year">2017</span>
    <span class="award-details">
      <span class="award-title">Alexander Rutherford Scholarship</span>, 
      <span class="award-org">Government of Alberta</span>
    </span>
  </li>

</ul>
<div class="service-category">
  <div class="service-title">Journal Peer Review</div>
  <ul class="service-list">
    <li class="service-item"><em>Cleaner Materials</em> <span class="if-badge">[IF: 9.0]</span></li>
    <li class="service-item"><em>Construction Innovation, Process, Management</em> <span class="if-badge">[IF: 3.9]</span></li>
    <li class="service-item"><em>Clean Technologies and Environmental Policy</em> <span class="if-badge">[IF: 4.5]</span></li>
    <li class="service-item"><em>Scientific Reports</em> <span class="if-badge">[IF: 3.9]</span></li>
    <li class="service-item"><em>Discovery Sustainability</em> <span class="if-badge">[IF: 3.6]</span></li>
  </ul>
</div>
