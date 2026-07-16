---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

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
    <div class="edu-details">Minor in Computer Science</div>
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

  /* Timeline Dot with Pulse Effect for Current Role */
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

</ul>
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
