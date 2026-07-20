---
layout: page
title: Projects
permalink: /projects/
description: Mobile programming coursework apps with screenshots and notes.
nav: true
nav_order: 1
---

{% include project_styles.liquid %}

Each project page includes screenshots, build notes, source links, and the main work inside the app.

## Android

<div class="project-page-grid">
  <article class="project-page-card accent-sky">
    <a class="project-page-image" href="{{ '/projects/hw1/' | relative_url }}">
      <img src="{{ '/assets/img/projects/hw1/course-list.png' | relative_url }}" alt="Terminator course list">
    </a>
    <div class="project-page-body">
      <span class="project-page-type">HW1</span>
      <h2><a href="{{ '/projects/hw1/' | relative_url }}">Terminator</a></h2>
      <p>Android course browser and weekly schedule planner.</p>
      <ul>
        <li>Searches bundled course data by name, instructor, id, and number.</li>
        <li>Builds a saved weekly plan.</li>
        <li>Checks duplicate courses, class conflicts, and exam conflicts.</li>
      </ul>
      <div class="project-link-row">
        <a href="{{ '/projects/hw1/' | relative_url }}">Project page</a>
        <a href="https://github.com/Mobile-Programming-HWs/HW1" target="_blank">Source repo</a>
      </div>
    </div>
  </article>
  <article class="project-page-card accent-green">
    <a class="project-page-image" href="{{ '/projects/hw2/' | relative_url }}">
      <img src="{{ '/assets/img/projects/hw2/question.png' | relative_url }}" alt="Quiz of Kings question screen">
    </a>
    <div class="project-page-body">
      <span class="project-page-type">HW2</span>
      <h2><a href="{{ '/projects/hw2/' | relative_url }}">Quiz of Kings</a></h2>
      <p>Android trivia game with local users, settings, saved scores, and a scoreboard.</p>
      <ul>
        <li>Fetches live questions from Open Trivia DB.</li>
        <li>Keeps fallback questions for offline play.</li>
        <li>Stores users, settings, and scores in Room.</li>
      </ul>
      <div class="project-link-row">
        <a href="{{ '/projects/hw2/' | relative_url }}">Project page</a>
        <a href="https://github.com/Mobile-Programming-HWs/HW2" target="_blank">Source repo</a>
      </div>
    </div>
  </article>
  <article class="project-page-card accent-red">
    <a class="project-page-image" href="{{ '/projects/project/' | relative_url }}">
      <img src="{{ '/assets/img/projects/project/courses.png' | relative_url }}" alt="MicroMaster courses screen">
    </a>
    <div class="project-page-body">
      <span class="project-page-type">Final project</span>
      <h2><a href="{{ '/projects/project/' | relative_url }}">MicroMaster</a></h2>
      <p>Android course and homework management app.</p>
      <ul>
        <li>Supports teacher, TA, and student actions.</li>
        <li>Stores courses, enrollments, homework links, and login state.</li>
        <li>Downloads homework files with Android DownloadManager.</li>
      </ul>
      <div class="project-link-row">
        <a href="{{ '/projects/project/' | relative_url }}">Project page</a>
        <a href="https://github.com/Mobile-Programming-HWs/Project" target="_blank">Source repo</a>
      </div>
    </div>
  </article>
</div>

## Swift

<div class="project-page-grid">
  <article class="project-page-card accent-gold">
    <a class="project-page-image" href="{{ '/projects/swift/' | relative_url }}">
      <img src="{{ '/assets/img/projects/swift/swiftui-preview.svg' | relative_url }}" alt="Crypto Tracker SwiftUI preview">
    </a>
    <div class="project-page-body">
      <span class="project-page-type">Swift</span>
      <h2><a href="{{ '/projects/swift/' | relative_url }}">Crypto Tracker</a></h2>
      <p>Swift cryptocurrency tracker with terminal and SwiftUI flows.</p>
      <ul>
        <li>Uses local sample market data.</li>
        <li>Shows date range price history and summary values.</li>
        <li>Exports selected history rows as CSV.</li>
      </ul>
      <div class="project-link-row">
        <a href="{{ '/projects/swift/' | relative_url }}">Project page</a>
        <a href="https://github.com/Mobile-Programming-HWs/Swift" target="_blank">Source repo</a>
      </div>
    </div>
  </article>
</div>
