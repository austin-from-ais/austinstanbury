---
category: commercial
title: "UF: Virtual Pedagogical Agents"
short_title: Virtual Pedagogical Agents
tagline: AI-powered learning in microelectronics through immersive applications
year: 2025
image: scale.png
features:
  - Context-aware GPT-powered pedagogical agent with awareness of student progress, held objects, and learning context
  - Interactive LEGO-like assembly experiences for semiconductor packaging structures (CoWoS, Foveros, InFO-PoP)
  - Virtual X-ray tomography lab simulating hands-on equipment operation and microchip quality analysis
  - Both desktop and Mixed Reality versions enabling comparative learning modality research
  - 3D robot avatar with ElevenLabs voice for consistent pedagogical presence
  - Longitudinal assessment design measuring retention at 24 hours and 6 weeks post-intervention
tech: Built in Unity 2022.3.40f with XR Interaction Toolkit v3.0.7 and XR Hands v1.4.3 for hand tracking. 3D chip packaging models created in Maya. GPT integration via fine-tuned CustomGPT models trained on domain-specific microelectronics data. Deployed on Meta Quest 3 for MR conditions and WebGL for PC conditions. Voice synthesis through ElevenLabs. Applications available on Meta Store and GitHub.
links:
  - label: "CHI '26 Paper: Facilitating Hands-On Learning in Microelectronics Education through Mixed Reality and AI Pedagogical Agents (conditionally accepted)"
    url: "#"
note: "$450K funded by Department of Defense and National Science Foundation in collaboration with Purdue University and SCALE initiative. Presented at IEEE PAINE, SCALE-Con in Washington DC, ACM CHI 2025 in Yokohama, and ACM CSCW 2025 in Bergen. Also published at ACM CHI EA 2025, ACM CSCW Companion 2025, and Computers and Education: Artificial Intelligence (2026)."
---

Virtual Pedagogical Agents is a suite of desktop and Mixed Reality applications for microelectronics education that combine interactive learning modules with context-aware AI tutoring. Students learn by directly interacting with 3D models of chip packaging structures—toggling component visibility, scaling objects for closer inspection, and assembling components in LEGO-like exercises that build visual-spatial understanding of complex semiconductor architectures. A GPT-powered virtual tutor accompanies students throughout, answering context-specific questions in real time, aware of what the student is holding, their progress, what they're learning, and their prior conversation history.

**Research Findings**

Our comparative studies produced several key insights. In a between-subjects study comparing PC and Mixed Reality versions of the CoWoS assembly experience, both conditions produced significant learning gains with different temporal profiles: PC users showed stronger immediate knowledge acquisition (89% vs 73% normalized gain), while MR users demonstrated more stable retention at six weeks, with PC scores declining significantly over that period while MR scores held steady. MR also produced significantly higher engagement.

A second factorial experiment examining GPT integration and 3D avatar presence in a virtual X-ray tomography lab found that GPT chat significantly improved social presence, perceived knowledge gain, and actual quiz performance. The 3D avatar enhanced social presence and perceived learning but did not independently improve quiz scores.

These findings informed a broader scoping review synthesizing 54 studies on AI and XR for personalized learning, mapping how contextual AI is deployed in immersive educational environments and identifying critical gaps in multimodal input utilization, long-term assessment, and learner profile integration.

**Impact**

This work has also given birth to the PATHS program at UF, designed to help autistic adults find career opportunities in the microelectronics industry.

Built with Serene Cheon, Juan Francisco Lam, Hyo Kang, Pavanbabu Arjunamahanthi, Himanandhan Reddy Kottur, Navid Asadizanjani, Kun Xu, Zifeng Liu, Xinyue Jiao, and Wanli Xing.
