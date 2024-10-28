---
title: 'A Whole-Body Compliance Control Strategy of Truss Crawling for Multi-Arm Space Robots'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zijian,Dai
  - Peiji,Wang
  - Tao,Lin
  - Chengfei,Yue

# Author notes (optional)

date: '2024-05-01T00:15:39Z'
# doi: 'https://www.sys-ele.com/EN/10.12305/j.issn.1001-506X.2023.11.27'

# Schedule page publish date (NOT publication's date).

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-journal']

# Publication name and optional abbreviated publication name.
publication: In *ICGNC 2024 (Accepted)*
publication_short: In *ICGNC 2024 (Accepted)*

abstract: The on-orbit service technologies such as on-orbit assembly, inspection and maintenance of large spacecraft have become significant development direction in the future. Multi-arm space robots, capable of high-risk and high-load tasks, can move on the space truss and complete on-orbit assembly and maintenance tasks. These robots have broad application prospects in on-orbit services, where their precise and stable movement capabilities are crucial for mission success. However, during contact motion and closed-loop motion, the lack of compliance in multiarm space robots may result in excessive force or torque on the target, potentially damaging the robot itself or the spacecraft equipment. Therefore, we propose a whole-body compliance control strategy (WBCC) for the motion of multi-arm space robots to reduce the risks of space truss crawling. The WBCC includes a unified compliance model consisting of a cartesian compliance model for the ends and a virtual spring model of the floating base. We use the MPC method to optimize the contact force of the effector to solve contact stability problem caused by the interaction between the robot and the rigid truss. Also, we embed it in the WBCC to ensure the motion stability during crawling. Finally, we verify the control strategy in Isaac Sim, and the simulation results indicate that the strategy can achieve compliance control for multi-arm robots during space truss crawling.

# Summary. An optional shortened abstract.
summary: This paper presents a WBCC strategy for multi-arm robots to achieve compliant crawling on space trusses.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_source: 'https://www.sys-ele.com/EN/10.12305/j.issn.1001-506X.2023.11.27'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
  # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
