---
layout: page
title: Crypto Tracker
description: Swift cryptocurrency tracker with terminal and SwiftUI flows
img: assets/img/projects/swift/swiftui-preview.svg
importance: 4
category: swift
---

[Source repo](https://github.com/Mobile-Programming-HWs/Swift){:target="\_blank"} | [README](https://github.com/Mobile-Programming-HWs/Swift#readme){:target="\_blank"}

Crypto Tracker is a Swift cryptocurrency tracker with a terminal app, reusable core package, tests, and a SwiftUI playground. It uses local sample data and deterministic price history, so it does not need an API key or network access.

## Screens

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/swift/terminal-home.svg" title="Crypto Tracker terminal home" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/swift/terminal-history.svg" title="Crypto Tracker terminal history" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/swift/swiftui-preview.svg" title="Crypto Tracker SwiftUI preview" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">Terminal menus, price history, CSV output, and SwiftUI preview.</div>

## Built Work

- Lists default cryptocurrencies with today's price.
- Opens details by id, name, or symbol.
- Shows daily prices for a selected date range.
- Shows first, last, low, high, average, and change.
- Prints a selected range as CSV.
- Adds and deletes cryptocurrencies with validation.
- Includes profile editing in terminal and SwiftUI flows.

## Run

```powershell
cd "C:\Users\imanm\Downloads\GitHub\Mobile-Programming-HWs\Swift"
swift run crypto-tracker
```
