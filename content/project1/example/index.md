---
title: Wheeled Climbing Robot
summary: A wheeled robot that can climb slopes from 0 to 35 angles.
tags:
  - Robot platform building
date: '2020-10-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

# links:
#   - icon: youtube
#     icon_pack: fab
#     name: Bilibli
#     url: https://www.bilibili.com/video/BV1Xp4y1A7MT/?spm_id_from=333.999.0.0
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

The robot uses an acrylic plate underbody support structure, and uses a linear CCD camera to collect black squares to follow the track on slpoe; PWM is sent to the MSP430 platform controller through the ADC channel, and the encoder is used to measure the motor speed at all times.
