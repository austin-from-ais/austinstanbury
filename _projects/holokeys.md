---
category: grad-school
title: "HoloKeys: AR Music Education"
short_title: HoloKeys
tagline: Remote piano education combining augmented reality with IoT to let instructors physically play a student's piano from anywhere
year: 2021
image: holokeys.jpg
features:
  - Instructor sees a holographic piano on an AR headset and uses hand gestures to play it remotely
  - Each gesture triggers a physical key press on the student's real-world piano via wifi-enabled microcontrollers and servo motors
  - Custom clip system for attaching servos to piano keys — portable and compatible with any keyboard
  - Low-cost, two-component system requiring no modification to the student's existing instrument
tech: Built in Unity with the Lumin SDK for Magic Leap hand tracking. Real-time communication between AR interface and piano apparatus via PubNub API. Hardware side uses an ESP8266 microcontroller, PCA9685 servo driver board, and MG995 servo motors programmed in Arduino IDE.
links:
  - label: ACM VRST Paper
    url: https://doi.org/10.1145/3489849.3489921
highlights:
  title: "Project Highlights:"
  items:
    - "Published at ACM VRST 2021 in Osaka, Japan"
    - "Principal Investigator on UF College of the Arts Strategic Opportunity Fund grant ($5,000)"
    - "Addresses critical gaps in remote music education where live demonstration is essential"
---

HoloKeys is a remote piano education system that combines augmented reality with IoT hardware to enable instructors to physically play a student's piano from a remote location. The instructor wears an AR headset and sees a holographic replica of the student's piano overlaid in their environment. Using hand gestures, they play the holographic keys—each gesture triggers a corresponding physical key press on the student's real-world piano via wifi-enabled microcontrollers and servo motors. The system addresses critical challenges in remote music education, where live demonstration and player synchronization are essential but difficult to achieve through conventional video conferencing.

**How It Works**

The instructor launches HoloKeys on a Magic Leap headset and a 3D holographic piano appears in their space. Hand tracking detects the instructor's gestures, and a raycast highlights the nearest key. A pinch gesture triggers a key press event, which is published in real time via PubNub to the student side. There, an ESP8266 microcontroller receives the message and commands the servo motors to physically depress the corresponding key on the student's piano.

The hardware side uses a custom clip system that attaches servo motors directly to piano keys. The system is portable, requires no permanent modification, and works with keyboards students already own. A PCA9685 servo driver board manages the motors, and the entire student-side apparatus connects over wifi.

**Context**

The project was developed during the COVID-19 pandemic, when remote instruction became the norm across education. Music education was particularly affected—conventional video calls introduce latency and remove the ability for an instructor to physically demonstrate on the student's instrument. HoloKeys was designed to restore that capability without requiring expensive equipment or complex setup.

**Publication**

The work was published at the ACM Symposium on Virtual Reality Software and Technology (VRST '21) in Osaka, Japan as "HoloKeys: Interactive Piano Education Using Augmented Reality and IoT" with Ines Said and Hyo Jeong Kang.

Built with Ines Said and Hyo Jeong Kang at the University of Florida.
