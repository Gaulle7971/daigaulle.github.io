---
title: Two-wheeled balancing robot
summary: Motor control method using two-level stage PID.
tags:
  - Robot platform building
date: '2020-03-01T00:00:00Z'

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

The internal and external PID dual control loops of the motor, of which the internal control loop: the PID position loop calculated by the AB phase of the Hall encoder; External control loop: the deviation steering loop of the Gyro angle.
