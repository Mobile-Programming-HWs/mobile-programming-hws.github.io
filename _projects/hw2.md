---
layout: page
title: Quiz of Kings
description: Android trivia game with local users and scores
img: assets/img/projects/hw2/game.png
importance: 2
category: android
---

[Source repo](https://github.com/Mobile-Programming-HWs/HW2){:target="_blank"} | [README](https://github.com/Mobile-Programming-HWs/HW2#readme){:target="_blank"}

Quiz of Kings is an Android trivia game with local login, settings, saved scores, and a scoreboard. It uses Open Trivia DB for live questions and keeps a cached fallback game for offline or failed request cases.

## Screens

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/hw2/login.png" title="Quiz of Kings login" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/hw2/game.png" title="Quiz of Kings game setup" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/hw2/question.png" title="Quiz of Kings question" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">Login, quiz setup, and the question flow.</div>

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/projects/hw2/settings.png" title="Quiz of Kings settings" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/projects/hw2/scoreboard.png" title="Quiz of Kings scoreboard" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">Settings and scoreboard screens give the game more than a single play screen.</div>

## Built Work

- Registers and logs in local users.
- Saves settings and scores in Room.
- Fetches live questions from Open Trivia DB.
- Falls back to cached questions when needed.
- Tracks score, progress, category, difficulty, and question count.
- Shows profile, settings, drawer, and scoreboard screens.

## Run

```powershell
cd "C:\Users\imanm\Downloads\GitHub\Mobile-Programming-HWs\HW2"
.\gradlew.bat :app:assembleDebug
```
