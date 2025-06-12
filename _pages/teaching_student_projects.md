---
layout: single
title: "Teaching & Student projects"
permalink: /teaching_student_projects/
author_profile: true
---

# 1. Teaching
<ul>
  <li>Robot Design and Simulation</li>
  <ul>
    <li>Subject of the M.S. degree in Automation and Robotics Engineering.</li>
    <li>Times taught: 1 (2024/2025).</li>
    <li><a href = "https://cvnet.cpd.ua.es/Guia-Docente/GuiaDocente/Index?wlengua=en&wcodasi=37816&scaca=2024-25">More info available here.</a></li>
  </ul>
  <li>Systems and Instruments Foundations</li>
  <ul>
    <li>Subject of the B.S. degree in Biomedical Engineering.</li>
    <li>Times taught: 1 (2024/2025).</li>   
    <li><a href = "https://cvnet.cpd.ua.es/Guia-Docente/?wlengua=en&wcodasi=33612&scaca=2024-25">More info available here.</a></li>
  </ul>
  <li>Human-Machine Interaction Systems</li>
  <ul>
    <li>Subject of the M.S. degree in Automation and Robotics Engineering. </li>
    <li>Times taught: 1 (2024/2025).</li>   
    <li><a href = "https://cvnet.cpd.ua.es/Guia-Docente/?wlengua=en&wcodasi=37809&scaca=2024-25">More info available here.</a></li>
  </ul>  
  <li>Robot Mechanisms and Modelling</li>
  <ul>
    <li>Subject of the B.S. degree in Robotics Engineering.</li>
    <li>Times taught: 1 (2024/2025).</li>   
    <li><a href = "https://cvnet.cpd.ua.es/Guia-Docente/?wlengua=en&wcodasi=33719&scaca=2024-25">More info available here.</a></li>
  </ul>  
</ul>

# 2. Student projects
Student projects are within [AUtomatics, RObotics and Artificial Vision (AUROVA)](http://www.aurova.ua.es/) laboratory.

## Open Projects:

Currently none.

Contact [me](https://cvnet.cpd.ua.es/curriculum-breve/en/paez-ubieta-ignacio-de-loyola/204002), [Dr. Santiago T. Puente](https://cvnet.cpd.ua.es/curriculum-breve/es/puente-mendez-santiago-timoteo/2771) or [Dr. Francisco Candelas](https://cvnet.cpd.ua.es/curriculum-breve/es/candelas-herias-francisco-andres/11597) if you would like to propose one.



<!-- # Past Projects: -->
## Past student projects:
### Reward design automation with LLMs for robotic manipulation
2025 Bachelor Degree Thesis by Moisés Fernández Herrero
<br>
<div style="text-align:justify;">
Manual reward design for Reinforcement Learning (RL) in robotics is both complex and error-prone. This work examines automating that process through Large Language Models (LLMs), extending the Eureka methodology. We assess various commercial LLMs, beyond GPT-4 and GPT-3.5 from the original study, to generate rewards in three robotic manipulation tasks involving the Shadow and Allegro hands in the Isaac Gym simulator. Findings indicate that LLMs, especially recent models and those with Chain-of-Thought reasoning, outperform human-engineered rewards in 100% of the tasks tested, achieving success in high-complexity settings such as pen spinning with the Allegro Hand. Models like O1 and certain Claude variants stand out. The study confirms the strong potential of LLMs to optimize reward design for RL in complex robotics.
</div>
<br>
<!--[Full thesis](https://rua.ua.es/dspace/bitstream/10045/145137/1/TFM-Daniel-Frau-Alfaro.pdf)-->
[Published article](http://hdl.handle.net/10045/154455)

### Learning for manipulation using UR5e
2024 Master Degree Thesis by Daniel Frau Alfaro
<br>
<div style="text-align:justify;">
Reinforcement Learning is a discipline that allows the creation of policies and functions that generate control actions for a system given a state. These produce a change in the environment and generate an associated reward. Artificial Intelligence and Deep Learning neural models allow the estimation of these functions to operate in high dimensional domains even in situations where there is a continuous modelling of the system. In this Master's Thesis (TFM) an agent for the control of a UR5e manipulator robot has been developed to perform a reaching task to an object given only visual feedback from the environment. The object is then manipulated by means of classical control techniques. In addition, orientation is included as an objective together with the positioning of the robot at the desired point. For this purpose, the use of dual quaternions is proposed, a tool that allows the encoding of transformations in space in a compact and unified way. The theoretical aspects of the system related to the reinforcement methods and the robotic modelling of the system, together with the design decisions of the agents and the environment, are addressed in this report. In addition, the results obtained in both training and test stages in reaching and grasping tasks with classical control are shown.
</div>
<br>
[Full thesis](https://rua.ua.es/dspace/bitstream/10045/145137/1/TFM-Daniel-Frau-Alfaro.pdf)
[Published article](https://www.doi.org/10.1109/ROBOT61475.2024.10796878)

### Demonstrative dual grip using two UR5e controlled in ROS
2023 Bachelor Degree Thesis by Daniel Frau Alfaro
<br>
<div style="text-align:justify;">
This project involves the teleoperation of two UR5e arms. The position/speed control must be implemented, allowing it to be controlled by two Phantom Omni. Work will first have to be carried out on the simulation using rviz and the connection with the Phantoms, to subsequently adjust the controller to the system made up of the two real UR5e arms. The whole implementation will be made to work in ROS as a library.
</div>
<br>
[Full thesis](https://rua.ua.es/dspace/bitstream/10045/135243/1/Agarre_dual_demostrativo_mediante_dos_UR5e_controlados_en_Frau_Alfaro_Daniel.pdf)
[Published article](https://www.doi.org/10.1007/978-3-031-58676-7_36)

<!-- load profiles in the _teaching repo -->
<!-- {% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %} -->
