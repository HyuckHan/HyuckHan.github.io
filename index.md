---
layout: default
title: Home
---

<section class="hero" aria-labelledby="profile-name">
  <div class="hero__content">
    <p class="eyebrow">Computer Systems Researcher &amp; Educator</p>
    <h1 id="profile-name">Hyuck Han <span lang="ko">한혁</span></h1>
    <p class="hero__role">
      Associate Professor<br>
      <span>Department of Computer Science</span><br>
      <span>Dongduk Women’s University</span>
    </p>
    <div class="hero__links" aria-label="Profile links">
      <a href="#contact">Contact</a>
      <a href="{{ site.author.linkedin }}" rel="me noopener noreferrer">LinkedIn</a>
      <a href="{{ site.author.github }}" rel="me noopener noreferrer">GitHub</a>
    </div>
  </div>
</section>

<section id="about" class="section section--intro" aria-labelledby="about-heading">
  <div class="section__heading">
    <p class="section__number" aria-hidden="true">01</p>
    <h2 id="about-heading">About</h2>
  </div>
  <div class="section__body prose">
    <p>
      I am an Associate Professor in the Department of Computer Science at
      Dongduk Women’s University in Seoul, South Korea. My work focuses on
      computer systems, spanning system software, operating systems, databases,
      distributed and cloud systems, computer architecture, and AI accelerators.
    </p>
  </div>
</section>

<section id="research" class="section" aria-labelledby="research-heading">
  <div class="section__heading">
    <p class="section__number" aria-hidden="true">02</p>
    <h2 id="research-heading">Research Interests</h2>
  </div>
  <div class="section__body">
    <ul class="interest-list">
      {% for interest in site.research_interests %}
        <li>{{ interest }}</li>
      {% endfor %}
    </ul>
  </div>
</section>

<section id="education" class="section" aria-labelledby="education-heading">
  <div class="section__heading">
    <p class="section__number" aria-hidden="true">03</p>
    <h2 id="education-heading">Education</h2>
  </div>
  <div class="section__body">
    <ol class="timeline">
      <li class="timeline__item">
        <p class="timeline__date"><time datetime="2011-02">February 2011</time></p>
        <h3>Ph.D. in Computer Science and Engineering</h3>
        <p>Seoul National University</p>
      </li>
      <li class="timeline__item">
        <p class="timeline__date"><time datetime="2006-02">February 2006</time></p>
        <h3>M.S. in Computer Science and Engineering</h3>
        <p>Seoul National University</p>
      </li>
      <li class="timeline__item">
        <p class="timeline__date"><time datetime="2003-08">August 2003</time></p>
        <h3>B.S. in Computer Science and Engineering</h3>
        <p>Seoul National University</p>
      </li>
    </ol>
  </div>
</section>

<section id="experience" class="section" aria-labelledby="experience-heading">
  <div class="section__heading">
    <p class="section__number" aria-hidden="true">04</p>
    <h2 id="experience-heading">Professional Experience</h2>
  </div>
  <div class="section__body">
    <ol class="timeline">
      <li class="timeline__item">
        <p class="timeline__date">Current</p>
        <h3>Associate Professor</h3>
        <p>Department of Computer Science, Dongduk Women’s University</p>
      </li>
      <li class="timeline__item">
        <p class="timeline__date">
          <time datetime="2012-09">September 2012</time> – <time datetime="2014-02">February 2014</time>
        </p>
        <h3>Senior Engineer</h3>
        <p>Memory Solutions Lab, Samsung Electronics</p>
      </li>
      <li class="timeline__item">
        <p class="timeline__date">
          <time datetime="2011-03">March 2011</time> – <time datetime="2012-08">August 2012</time>
        </p>
        <h3>Postdoctoral Researcher</h3>
        <p>Seoul National University</p>
      </li>
      <li class="timeline__item">
        <p class="timeline__date">
          <time datetime="2010-06">June 2010</time> – <time datetime="2010-08">August 2010</time>
        </p>
        <h3>Research Intern</h3>
        <p>National Institute of Informatics, Tokyo, Japan</p>
      </li>
      <li class="timeline__item">
        <p class="timeline__date">
          <time datetime="1999-09">September 1999</time> – <time datetime="2003-02">February 2003</time>
        </p>
        <h3>Software Developer</h3>
        <p>Delta Information and Communications</p>
      </li>
    </ol>
  </div>
</section>

<section id="contact" class="section section--contact" aria-labelledby="contact-heading">
  <div class="section__heading">
    <p class="section__number" aria-hidden="true">05</p>
    <h2 id="contact-heading">Contact</h2>
  </div>
  <div class="section__body contact-grid">
    <div>
      <h3>Email</h3>
      <ul class="contact-list">
        <li><a href="mailto:hhyuck@gmail.com">hhyuck@gmail.com</a></li>
        <li><a href="mailto:hhyuck96@dongduk.ac.kr">hhyuck96@dongduk.ac.kr</a></li>
      </ul>
    </div>
    <div>
      <h3>Office</h3>
      <address>
        B309, In-Moon-Kwan<br>
        Department of Computer Science<br>
        Dongduk Women’s University<br>
        23-1 Wolgok-dong, Seongbuk-gu<br>
        Seoul, South Korea
      </address>
    </div>
  </div>
</section>

<!--
  Future content templates

  When real content is ready, add sections with the IDs below and enable the
  matching navigation links in _includes/header.html.

  Reserved IDs: #teaching and #projects
-->
