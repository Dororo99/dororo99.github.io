---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Contact
======
* Email: [ldh991014@hanyang.ac.kr](mailto:ldh991014@hanyang.ac.kr)
* GitHub: [Dororo99](https://github.com/Dororo99)
* Affiliation: Department of Computer Science, Hanyang University

Education
======
* B.S. student, Department of Computer Science, Hanyang University, Seoul, Korea, Mar. 2023 - Present
  * GPA: 3.79 / 4.5

Research experience
======
* Sep. 2025 - Present: Research Intern, IRCV Lab, Hanyang University, Seoul, Korea
  * Development of online mapping and topology model in an end-to-end process.

* Jan. 2024 - Nov. 2024: Research Intern, AAIS Lab, Hanyang University, Seoul, Korea
  * Development of pathology foundation model.

Project experience
======
* Fault-Tolerant Autonomous Driving Controller using Reinforcement Learning
  * Project in the 2025 MATLAB AI Student Challenge.
  * Configured a perception unit using radar and cameras.
  * Developed an RL agent focused on collision avoidance during perception unit failures.
  * Established a simulation environment using MATLAB and Simulink.

* Development of a 2D Grid-Based Autonomous Driving Algorithm
  * Project in SMYD Club.
  * Applied path planning algorithms including A\*, Hybrid A\*, and RRT\*.
  * Implemented PID control for vehicle dynamics.

* Authenticity and Reliability Inspection with SNS Evaluation
  * Project in the 2024 KAIST Counter-Disinformation Challenge.
  * Evaluated account confidence scores using a strict algorithm.
  * Verified dataset similarity using GPT and BERT models.

* Development of the Pathology Foundation Model
  * Project in AAIS Lab student internship.
  * Developed a preprocessing algorithm for large-scale pathology image slides.
  * Improved patch extraction speed through the preprocessing algorithm.

* Reconstructing objects from different backgrounds in 3D space using 3D Gaussian Splatting
  * Graduation project.
  * Built a custom dataset from self-captured videos.
  * Extracted object-specific point clouds using COLMAP, Gaussian Grouping, and SAM.
  * Improved Gaussian mixture model performance using a clustering algorithm.

* Measuring product volume on a conveyor belt using a smartphone
  * Project in the 2023 CJ Logistics Future Technology Challenge.
  * Used image processing and computer vision techniques.
  * Measured dimensions of stationary and moving boxes.

* Shorti
  * Peer-to-peer travel connection service.
  * 2023 Tourism Generative Artificial Intelligence Hackathon.
  
Skills
======
* Programming: Python, C++, MATLAB/Simulink
* Deep learning: PyTorch, TensorFlow
* Computer vision, autonomous driving simulation, reinforcement learning, image preprocessing

Publications
======
{% assign publication_count = site.publications | size %}
{% if publication_count == 0 %}
* Publication entries will be added here.
{% else %}
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
{% endif %}
  
Awards
======
* Grand Prize, 2024 KAIST Counter-Disinformation Challenge, KAIST, Korea, Dec. 2024

English proficiency
======
* OPIC IH, Jul. 2025
* TOEIC 930, Jun. 2025

Certifications
======
* Korean History Proficiency Test Level 3
