---
layout: page
title: MicroMaster
description: Android course and homework management app
img: assets/img/projects/project/courses.png
importance: 3
category: Android
---

[Source repo](https://github.com/Mobile-Programming-HWs/Project){:target="\_blank"} | [README](https://github.com/Mobile-Programming-HWs/Project#readme){:target="\_blank"}

MicroMaster is the final Android project. It manages course creation, enrollments, homework links, profile data, and role-based actions for teachers, TAs, and students.

## Screens

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/project/login.png" title="MicroMaster login" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/project/register.png" title="MicroMaster register" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/project/courses.png" title="MicroMaster courses" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">Account flow and the main course list.</div>

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/projects/project/course-detail.png" title="MicroMaster course detail" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/projects/project/add-course.png" title="MicroMaster add course" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/projects/project/add-homework.png" title="MicroMaster add homework" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">Course details, course creation, and homework entry.</div>

<div class="row justify-content-sm-center">
  <div class="col-sm-5 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/projects/project/profile.png" title="MicroMaster profile" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">The profile screen summarizes role, courses, homework, and stored file state.</div>

## Built Work

- Registers local users with role selection.
- Lets teachers create courses and add homework links.
- Lets students enroll in courses.
- Lets TAs request course access and add homework after approval.
- Stores users, courses, enrollments, TA records, homework links, and login state in Room.
- Downloads homework files with Android DownloadManager.

## Run

```powershell
cd "C:\Users\imanm\Downloads\GitHub\Mobile-Programming-HWs\Project"
.\gradlew.bat :app:assembleDebug
```
