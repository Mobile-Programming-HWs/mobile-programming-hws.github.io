---
layout: page
title: Home
permalink: /
nav: false

announcements:
  enabled: false

latest_posts:
  enabled: false
---

# Mobile Programming HWs

This site collects the mobile programming coursework projects in one place. Each project page shows what the app does, the main implementation work, screenshots, setup notes, and links to the source repo.

## Projects

- [Terminator]({{ '/projects/hw1/' | relative_url }}), Android course browser and weekly schedule planner.
- [Quiz of Kings]({{ '/projects/hw2/' | relative_url }}), Android trivia game with local users and scores.
- [MicroMaster]({{ '/projects/project/' | relative_url }}), Android course and homework management app.
- [Crypto Tracker]({{ '/projects/swift/' | relative_url }}), Swift cryptocurrency tracker with terminal and SwiftUI flows.

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/hw1/course-list.png" title="Terminator course list" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/hw2/question.png" title="Quiz of Kings question screen" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/project/courses.png" title="MicroMaster courses screen" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">Screenshots from the Android projects.</div>

<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/projects/swift/swiftui-preview.svg" title="Crypto Tracker SwiftUI preview" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">SwiftUI preview from the Swift project.</div>

## Source

The source repos live in [Mobile-Programming-HWs](https://github.com/Mobile-Programming-HWs).
