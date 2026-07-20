---
layout: page
title: Terminator
description: Android course browser and weekly schedule planner
img: assets/img/projects/hw1/course-list.png
importance: 1
category: android
---

[Source repo](https://github.com/Mobile-Programming-HWs/HW1){:target="_blank"} | [README](https://github.com/Mobile-Programming-HWs/HW1#readme){:target="_blank"}

Terminator is an Android app for browsing course data and building a weekly class plan. It keeps the data local, lets the user search courses, and checks the selected plan for duplicate courses, class conflicts, and exam conflicts.

## Screens

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/hw1/course-list.png" title="Terminator course list" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/hw1/course-details.png" title="Terminator course details" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/hw1/weekly-chart.png" title="Terminator weekly chart" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">Course search, course details, and the weekly chart view.</div>

<div class="row justify-content-sm-center">
  <div class="col-sm-5 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/projects/hw1/drawer.png" title="Terminator navigation drawer" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">The drawer keeps the main course list and selected chart close together.</div>

## Built Work

- Loads bundled JSON course data from app resources.
- Groups courses by department.
- Searches by name, instructor, number, and id.
- Shows units, capacity, class time, and exam time.
- Stores selected courses in SharedPreferences.
- Rejects duplicate courses and time conflicts before saving.

## Run

```powershell
cd "C:\Users\imanm\Downloads\GitHub\Mobile-Programming-HWs\HW1"
.\gradlew.bat :app:assembleDebug
```
