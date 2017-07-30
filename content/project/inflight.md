+++
# Date this page was created.
date = "2016-04-27"

# Project title.
title = "Visual-Based In-Flight File Transfer"

# Project summary to display on homepage.
summary = "A visual content transmission based on QR codes is implemented for file transfer onboard an aircraft between two passengers who own Android smartphone devices."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "inflight.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["demo", "Image-processing", "error-correcting-codes"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++

{{< youtube X9ysYu9xGb8 >}}


This project targets a situation onboard a plane where two passengers, having Android smartphone devices, want to transmit a file from one phone’s SD-card to the other. Radio transmission is prohibited onboard, since it may interfere with the aircraft navigation and communication systems.  This leads to the need of finding an innovative way of transmission. This paper explains the development of such a technology, which is based on visual transmission via QR codes. Different QR codes have been implemented and tested for fast and reliable transfer of data. Our application can achieve a speed of more than 1 KB/s. The reliability depends on the QR code and the version selected. Testing shows that the best performance is attained with color QR codes. 

The project was implemented in the context of the KTH Master´s course: EQ2440 - Project in Wireless Communication.