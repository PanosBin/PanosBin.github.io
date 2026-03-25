---
layout: default
title: About
permalink: /
---

<div class="about">

  <!-- ── Photo & Social ─────────────────────────────────────────────── -->
  <div class="about__photo-col">
    <img class="about__photo"
         src="{{ site.author.photo }}"
         alt="Portrait of {{ site.author.name }}"
         loading="eager">

    <div class="about__social">
      <a class="about__social-link"
         href="https://github.com/{{ site.author.github }}"
         target="_blank" rel="noopener noreferrer">
        <i class="fab fa-github" aria-hidden="true"></i>
        <span>GitHub</span>
      </a>
      <a class="about__social-link"
         href="{{ site.author.linkedin }}"
         target="_blank" rel="noopener noreferrer">
        <i class="fab fa-linkedin" aria-hidden="true"></i>
        <span>LinkedIn</span>
      </a>
      <a class="about__social-link"
         href="mailto:{{ site.author.email }}">
        <i class="fas fa-envelope" aria-hidden="true"></i>
        <span>Email</span>
      </a>
      <a class="about__social-link" href="#">
        <i class="fas fa-map-marker-alt" aria-hidden="true"></i>
        <span>{{ site.author.location }}</span>
      </a>
    </div>
  </div>

  <!-- ── Bio & Content ──────────────────────────────────────────────── -->
  <div class="about__content">
    <h1>{{ site.author.name }}</h1>
    <p class="subtitle">
      MSc Student in Data Science &amp; AI<br>
      Maastricht University
    </p>

    <p class="about__tagline">
      Curious about data, cybersecurity, and AI. Always looking to learn something new and put it to use.
    </p>

<p>
  I am currently completing my MSc in Data Science for Decision Making at
  <a href="https://www.maastrichtuniversity.nl" target="_blank" rel="noopener noreferrer">Maastricht University</a>
  (expected May 2026), with a thesis on designing an LLM-integrated pipeline for Android vulnerability detection.
  I hold a BSc in Economics from the University of Macedonia, Thessaloniki, and a Pre-MSc in Data Science & AI from Maastricht University.
</p>

<p>
  My experience spans data science, bioinformatics, cybersecurity, and teaching. I have worked as a Data Science Intern at
  the Laboratory of Cellular Genomic Medicine (MUMC+)
  and currently serve as a Teaching Assistant at Maastricht University across multiple courses including NLP
  Cryptography, and Computer Security.
</p>

    <h3>Areas of Interest</h3>
    <ul class="interests-list">
      <li>Data Science &amp; Machine Learning</li>
      <li>Cybersecurity &amp; Cloud Security</li>
      <li>Financial Markets &amp; Algorithmic Trading</li>
      <li>Blockchain &amp; Decentralized Finance</li>
    </ul>

    <h3>Skills</h3>
    <div class="skill-tags">
      <span class="skill-tag">Python</span>
      <span class="skill-tag">R</span>
      <span class="skill-tag">Java</span>
      <span class="skill-tag">SQL</span>
      <span class="skill-tag">Linux</span>
      <span class="skill-tag">Git</span>
      <span class="skill-tag">Power BI</span>
      <span class="skill-tag">Solidity</span>
      <span class="skill-tag">Deep Learning</span>
      <span class="skill-tag">NLP</span>
      <span class="skill-tag">Azure</span>
      <span class="skill-tag">Data Engineering</span>
    </div>

    <h3>Awards &amp; Memberships</h3>
    <ul class="interests-list">
      <li><strong>MENSA International IQ Society</strong> &mdash; Top 2% IQ score (&ge;135)</li>

      <li><strong>Finance Club</strong> &mdash; University of Macedonia</li>
    </ul>

    <h3>Languages</h3>
    <div class="lang-bars">
      <div class="lang-item">
        <span class="lang-name">Greek</span>
        <span class="lang-level">Native</span>
      </div>
      <div class="lang-item">
        <span class="lang-name">English</span>
        <span class="lang-level">Full Professional</span>
      </div>
    </div>

  </div>

</div>
