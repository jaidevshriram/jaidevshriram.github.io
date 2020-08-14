---
layout: page
title: Smart Streetlight Controller
description: Automated streetlight control for IIIT, with live analytics and remote control functionality
img: /assets/img/purple.jpg
importance: 3
---

Central server/dashboard repository: <a href="https://github.com/nishant-sachdeva/DjangoServerEsw">https://github.com/nishant-sachdeva/DjangoServerEsw</a>

Mobile app repository: <a href="https://github.com/jaidevshriram/Remote-Controller-Streetlights">https://github.com/jaidevshriram/Remote-Controller-Streetlights</a>

The main goal with this project was to conserve energy used by IIIT's streetlights. The previous solution required a fixed time to automatically turn on/off. By moving to a completely automated solution that relies on daylight levels, the system automatically controls nearly all of IIIT's streetlights. To prevent accidental state changes, we also made a mobile app for security guards to use - with which they can switch the lights on/off, change modes. 

The project had 3 major parts: 

1. Arduino + OneM2M for the control logic
2. Central server for analytics + linking the mobile app and streetlights
3. Mobile application

To fully appreciate the usecase, the analytics provided show energy saved as well as the variance in on/off times across days.

Built in a team of 3 for the course 'Embedded Systems Workshop' at IIIT-H.