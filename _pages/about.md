---
layout: page
title: Mobile Programming HWs
permalink: /
nav: false

announcements:
  enabled: false

latest_posts:
  enabled: false
---

{% include project_styles.liquid %}

<div class="project-hub-lead">
  <div class="project-hub-copy">
    <span class="project-hub-kicker">Android and Swift coursework</span>
    <p class="project-hub-intro">This site is the public index for my mobile programming coursework. It keeps the finished apps, screenshots, build notes, and source links in one place.</p>
    <div class="project-hub-stats">
      <div class="project-hub-stat">
        <strong>6</strong>
        public repos
      </div>
      <div class="project-hub-stat">
        <strong>4</strong>
        app projects
      </div>
      <div class="project-hub-stat">
        <strong>2</strong>
        support repos
      </div>
    </div>
    <div class="project-action-row">
      <a class="project-action project-action-primary" href="{{ '/projects/' | relative_url }}">View projects</a>
      <a class="project-action" href="{{ '/repositories/' | relative_url }}">Open repos</a>
    </div>
  </div>
  <div class="project-hub-preview" aria-label="Project screenshots">
    <img src="{{ '/assets/img/projects/hw1/course-list.png' | relative_url }}" alt="Terminator course list" loading="eager">
    <img src="{{ '/assets/img/projects/hw2/question.png' | relative_url }}" alt="Quiz of Kings question screen" loading="eager">
    <img src="{{ '/assets/img/projects/project/course-detail.png' | relative_url }}" alt="MicroMaster course detail" loading="eager">
    <img src="{{ '/assets/img/projects/swift/swiftui-preview.svg' | relative_url }}" alt="Crypto Tracker SwiftUI preview" loading="eager">
  </div>
</div>

## Project Notes

<div class="project-hub-grid">
  <article class="project-hub-card accent-sky">
    <span class="project-hub-type">Android</span>
    <h2><a href="{{ '/projects/hw1/' | relative_url }}">Terminator</a></h2>
    <p>Course browser and weekly schedule planner.</p>
    <ul>
      <li>Course search and grouping</li>
      <li>Weekly chart view</li>
      <li>Conflict checks before saving</li>
    </ul>
  </article>
  <article class="project-hub-card accent-green">
    <span class="project-hub-type">Android</span>
    <h2><a href="{{ '/projects/hw2/' | relative_url }}">Quiz of Kings</a></h2>
    <p>Trivia game with local users, settings, and scores.</p>
    <ul>
      <li>Room backed score history</li>
      <li>Live questions with fallback data</li>
      <li>Profile and scoreboard screens</li>
    </ul>
  </article>
  <article class="project-hub-card accent-red">
    <span class="project-hub-type">Android</span>
    <h2><a href="{{ '/projects/project/' | relative_url }}">MicroMaster</a></h2>
    <p>Course and homework management app.</p>
    <ul>
      <li>Teacher, TA, and student flows</li>
      <li>Course enrollment records</li>
      <li>Homework links and downloads</li>
    </ul>
  </article>
  <article class="project-hub-card accent-gold">
    <span class="project-hub-type">Swift</span>
    <h2><a href="{{ '/projects/swift/' | relative_url }}">Crypto Tracker</a></h2>
    <p>Cryptocurrency tracker with terminal and SwiftUI flows.</p>
    <ul>
      <li>Local sample market data</li>
      <li>Date range price history</li>
      <li>CSV output and tests</li>
    </ul>
  </article>
</div>

## Source Repos

The source repos live in [Mobile-Programming-HWs](https://github.com/Mobile-Programming-HWs). The organization includes the app projects, this project site, and the public profile repo.
