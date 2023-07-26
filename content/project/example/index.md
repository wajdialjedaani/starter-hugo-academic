---
title: Test Smells
# summary: An example of using the in-built project page.
tags:
  - Test Smells
  # - Unit Test
  # - Software Quality
  # - Software Maintenance and Evolution
  
date: '2021-01-18T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

# image:
#   caption: Photo by rawpixel on Unsplash
#   focal_point: Smart

links:
  # - icon: twitter
  #   icon_pack: fab
  #   name: Follow
  #   url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Unit test code, just like regular/production source code, is subject to bad programming practices, also known as anti-patterns, defects, and smells. Smells, being symptoms of bad design or implementation decisions, has been proven to decrease the quality of software systems from various aspects, such as making it harder to understand, more complex to maintain, and more prone to errors bugs.

Test smells are defined as bad programming practices in unit test code (such as how test cases are organized, implemented, and interact with each other) that indicate potential design problems in the test source code.

This project aims to educate developers on the types of unit testing smells that developers typically introduce or encounter when writing unit tests. To this extent, this project seeks to extend the existing test smell catalog by adding new types of test smells. Additionally, we make available an open-source tool to detect the different smell types in the source code.

Using the updated test smell catalog and our test smell detection tool, we conduct multiple empirical studies on software systems to understand how test smells impact software maintenance and evolution activities.
