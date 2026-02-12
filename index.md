---
layout:     page
title:
permalink:  /
---

<!-- SEO Meta Tags -->
<meta name="title" content="Payam Parvizi | Reinforcement Learning & Control | Sim-to-Real Robotics" />
<meta name="description" content="PhD-trained Postdoctoral Research Associate at the University of Ottawa working on reinforcement learning and control for reliable continuous-control systems, with a focus on policy regularization, stability, and sim-to-real deployment." />
<meta name="keywords" content="Payam Parvizi, reinforcement learning, continuous control, control-oriented machine learning, policy regularization, stability, applied RL, sim-to-real, robotics, quadcopter, Gymnasium, MuJoCo, JAX, University of Ottawa, National Research Council Canada" />
<meta name="author" content="Payam Parvizi" />
<meta property="og:title" content="Payam Parvizi | Reinforcement Learning & Control | Sim-to-Real Robotics" />
<meta property="og:description" content="Research, publications, and projects by Payam Parvizi on reinforcement learning and control for reliable continuous-control systems, including sim-to-real deployment on physical platforms." />
<meta property="og:type" content="website" />
<meta property="og:url" content="https://payamparvizi.github.io/" />
<meta property="og:image" content="https://payamparvizi.github.io/img/Profile/headshot.jpg" />
---

<div id="intro">
    <div id="intro-text">
        <h1>Payam Parvizi</h1>
        <p align="justify">
            I am a PhD-trained Postdoctoral Research Associate with 4+ years of experience developing and validating reinforcement learning methods for continuous control under real-world-motivated constraints. I am driven by a deep curiosity about how learning-based controllers can achieve the smooth, stable, and reliable behavior needed for safe deployment in physical systems.
            <br><br>
            I specialize in action/policy regularization and policy smoothing to reduce high-frequency oscillations and improve reliability, validated through the development of custom Gymnasium-compatible environments and simulation-to-real transfer. My work includes deployment on quadcopter platforms and applications in satellite-to-ground optical communications, conducted at the <a href="https://www.uottawa.ca/en" target="_blank">University of Ottawa</a> under the supervision of <a href="https://uniweb.uottawa.ca/view/profile/members/175?lang=en" target="_blank">Dr. Davide Spinello</a> and <a href="https://www.uottawa.ca/faculty-engineering/school-electrical-engineering-computer-science/directory/colin-bellinger" target="_blank">Dr. Colin Bellinger</a>, and in collaboration with <a href="https://nrc.canada.ca/en/corporate/contact-us/nrc-directory-science-professionals/ross-cheriton" target="_blank">Dr. Ross Cheriton</a> at the <a href="https://nrc.canada.ca/" target="_blank">National Research Council of Canada (NRC)</a>.
            <br><br>
            <br><br>
            <a href="Resume.pdf" target="_blank">CV</a>&nbsp;&nbsp;&nbsp;&nbsp;
            <a href="https://scholar.google.com/citations?user=nZz4fKIAAAAJ&hl=en" target="_blank">Google Scholar</a>&nbsp;&nbsp;&nbsp;&nbsp;
            <a href="https://github.com/payamparvizi" target="_blank">GitHub</a>&nbsp;&nbsp;&nbsp;&nbsp;
            <a href="https://www.linkedin.com/in/PayamParvizi" target="_blank">LinkedIn</a>&nbsp;&nbsp;&nbsp;&nbsp;
            <a href="mailto:pparv056@uottawa.ca" target="_blank">Email</a>
        </p>
    </div>
    <div id="intro-image">
        <img src="/img/Profile/IMG_0759.jpg">
    </div>
</div>


<br><br><br>
<div id="filters" class="button-group">
    <!-- <button class="button is-checked" data-filter=".research">Highlights</button> -->
    <button class="button" data-filter=".research">Research</button>
    <button class="button" data-filter=".publication">Publications</button>
    <button class="button" data-filter=".talk">Talks</button>
    <button class="button" data-filter=".experience">Experience</button>
</div>


<div class="grid">
<style>
  .talks-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 2em;
    margin-bottom: 2em;
  }
  .talks-grid .talk {
    box-sizing: border-box;
    padding: 1em;
    border: 1px solid #eee;
    border-radius: 8px;
    background: #fafbfc;
    margin-bottom: 0;
  }
  @media (max-width: 1200px) {
    .talks-grid {
      grid-template-columns: repeat(2, 1fr);
    }
  }
  @media (max-width: 900px) {
    .talks-grid {
      grid-template-columns: 1fr;
    }
  }
</style>
    <!-- Research -->
 <!-- Research -->
<div class="list-item research-project research" data-category="research">
    <a href="#" onclick="event.preventDefault()" class="research-thumbnail">
        <img src="/img/sapps.png" alt="Adaptive Policy Regularization for Smooth Control in Reinforcement Learning" />
    </a>
    <div class="research-description">
        <h3>Adaptive Policy Regularization for Smooth Control in Reinforcement Learning</h3>
        <p>
        This work introduces State-Adaptive Proportional Policy Smoothing (SAPPS), a lightweight
        policy regularization method that suppresses high-frequency action oscillations in continuous-control
        reinforcement learning while preserving responsiveness to rapid state changes.<br><br>
        The method is validated across MuJoCo benchmarks, an adaptive optics system, and sim-to-real quadcopter experiments.<br><br>
        <i>
        PhD research conducted at the <a href="https://www.uottawa.ca/en" target="_blank">University of Ottawa</a>
        in collaboration with the <a href="https://nrc.canada.ca/" target="_blank">National Research Council of Canada (NRC)</a>.
        </i>
        </p>
    </div>
</div>


<div class="list-item research-project research" data-category="research">
    <a href="#" onclick="event.preventDefault()" class="research-thumbnail">
        <video controls muted loop playsinline poster="/img/Quadcopter_Sim_to_real.png">
            <source src="/img/Quadcopter_Sim_to_real.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </a>
    <div class="research-description">
        <h3>Sim-to-Real Reinforcement Learning for Quadrotor Control</h3>
        <p>
        This work develops a sim-to-real reinforcement learning framework for quadrotor control
        using the Proximal Policy Optimization (PPO). A training is designed
        for both simulation and real-world deployment on the Crazyflie 2.1 nano-quadrotor,
        enabling stable hovering control.<br><br>
        <a href="https://github.com/payamparvizi/Crazyflie_RL" target="_blank">[Code]</a>
            <br><br>
            <br><br>
        </p>
    </div>
</div>


<div class="list-item research-project research" data-category="research">
    <a href="#" onclick="event.preventDefault()" class="research-thumbnail">
        <img src="/img/WFAO.png" alt="Wavefront Sensorless Adaptive Optics (WSL-AO) with Reinforcement Learning" />
    </a>
    <div class="research-description">
        <h3>Reinforcement Learning for Wavefront Sensorless Adaptive Optics</h3>
        <p>
        This work develops a simulated wavefront sensorless adaptive optics (AO) reinforcement learning (RL) environment for 
        training and evaluating RL algorithms. It is the first AO–RL environment implemented using the OpenAI Gymnasium 
        framework, enabling reproducible benchmarking and analysis. The work also demonstrates, for the first time, 
        the potential of reinforcement learning for wavefront sensorless AO in satellite communication downlinks.<br><br>
        <i>
        PhD research conducted in collaboration with the 
        <a href="https://nrc.canada.ca/" target="_blank">National Research Council of Canada (NRC)</a>.
        </i>
        </p>
    </div>
</div>


<div class="list-item research-project research" data-category="research">
    <a href="#" onclick="event.preventDefault()" class="research-thumbnail">
        <img src="/img/area-coverage.png" alt="Multi-Robot Area Coverage Control with Repulsive Density" />
    </a>
    <div class="research-description">
        <h3>Multi-Robot Area Coverage Control with Repulsive Risk Density</h3>
        <p>
        This work formulates an area coverage control problem for multi-agent systems operating under
        partial environmental information. Mobile targets are modeled as risk sources, and the risk
        density is incorporated directly into the agent dynamics as a repulsive term, enabling online
        motion planning in service robotics applications.<br><br>
        <i>
        PhD Research in Multi-Robot Area Coverage, supervised by
        <a href="https://uniweb.uottawa.ca/view/profile/members/175?lang=en" target="_blank">Dr. Davide Spinello</a>
        at <a href="https://www.uottawa.ca/en" target="_blank">University of Ottawa</a>.
        </i>
        </p>
    </div>
</div>

<div class="list-item research-project research" data-category="research">
    <a href="#" onclick="event.preventDefault()" class="research-thumbnail">
        <img src="/img/robotic-deburring.png" alt="Robotic Deburring via Learning from Demonstration" />
    </a>
    <div class="research-description">
        <h3>Robotic Deburring via Learning from Demonstration</h3>
        <p>
        This work presents a learning-from-demonstration approach for robotic deburring of
        workpieces with unknown shapes. Task-relevant motions of a human expert were recorded
        using a 6-DOF haptic device and encoded using augmented
        Dynamic Movement Primitives (DMPs) to generate adaptable deburring trajectories.<br><br>
        <i>
        M.Sc. research, part of the
        <a href="https://open.metu.edu.tr/handle/11511/50548" target="_blank">“Development of a High-Precision Hybrid Robotic Deburring System”</a>
        project funded by <a href="https://tubitak.gov.tr/en" target="_blank">TÜBİTAK</a>.
        </i>
        </p>
    </div>
</div>
<!-- -->
    <!-- Publications -->
    <!-- -->
<div class="list-item publication" data-category="publication">
    <a href="https://www.techrxiv.org/doi/full/10.36227/techrxiv.177004949.91897305" class="thumbnail" target="_blank">
        <img src="/img/sapps.png" alt="Adaptive Policy Regularization for Smooth Control in Reinforcement Learning" />
    </a>
    <div class="project-description">
        <h3>
            <a href="https://www.techrxiv.org/doi/full/10.36227/techrxiv.177004949.91897305" target="_blank">
                Adaptive Policy Regularization for Smooth Control in Reinforcement Learning
            </a>
        </h3>
        <p>
            <b>Payam Parvizi</b>, Abhishek Naik, Colin Bellinger, Ross Cheriton, Davide Spinello<br>
            <i>Authorea, 2026. Submitted to IEEE Transactions on Automation Science and Engineering</i><br>
            <a href="https://www.techrxiv.org/doi/full/10.36227/techrxiv.177004949.91897305" target="_blank">Paper</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
            <a href="https://github.com/payamparvizi/sapps-rl" target="_blank">Code</a>
        </p>
    </div>
</div>
<div class="list-item publication" data-category="publication">
    <a href="https://ruor.uottawa.ca/items/9fc2648b-795e-4664-9f85-994c346dc621" class="thumbnail">
        <img src="/img/PhD_thesis.png" alt="PhD Thesis: Adaptive Policy Smoothing in Reinforcement Learning" />
    </a>
    <div class="project-description">
        <h3>
            <a href="https://ruor.uottawa.ca/items/9fc2648b-795e-4664-9f85-994c346dc621" target="_blank">
                Adaptive Policy Smoothing in Reinforcement Learning: Applications to Wavefront Sensorless Adaptive Optics and Robotics
            </a>
        </h3>
        <p>
            <b>Payam Parvizi</b><br>
            <i>Ph.D. Thesis, University of Ottawa, 2025</i><br>
            <a href="https://ruor.uottawa.ca/items/9fc2648b-795e-4664-9f85-994c346dc621" target="_blank">Ph.D. Thesis</a>
        </p>
    </div>
</div>
<div class="list-item publication" data-category="publication">
    <a href="https://doi.org/10.1364/opticaopen.30043543" class="thumbnail" target="_blank">
        <img src="/img/WFAO.png" alt="Action-Regularized Reinforcement Learning for Adaptive Optics" />
    </a>
    <div class="project-description">
        <h3>
            <a href="https://doi.org/10.1364/opticaopen.30043543" target="_blank">
                Action-Regularized Reinforcement Learning for Adaptive Optics in Optical Satellite Communication
            </a>
        </h3>
        <p>
            <b>Payam Parvizi</b>, Colin Bellinger, Ross Cheriton, Abhishek Naik, Davide Spinello<br>
            <i>Optica Open, 2025. In final production at Journal of the Optical Society of America B (Optica)</i><br>
            <a href="https://doi.org/10.1364/opticaopen.30043543" target="_blank">Paper</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
            <a href="https://github.com/payamparvizi/wavefront-sensorless-adaptive-optics-rl" target="_blank">Code</a>
        </p>
    </div>
</div>
    <div class="list-item publication" data-category="publication">
    <a href="https://www.mdpi.com/2304-6732/10/12/1371" class="thumbnail" target="_blank">
        <img src="/img/wslao_mdpi.png" alt="RL Environment for Wavefront Sensorless Adaptive Optics" />
    </a>
    <div class="project-description">
        <h3>
            <a href="https://www.mdpi.com/2304-6732/10/12/1371" target="_blank">
                Reinforcement Learning Environment for Wavefront Sensorless Adaptive Optics in Single-Mode Fiber-Coupled Optical Satellite Communications Downlinks
            </a>
        </h3>
        <p>
            <b>Payam Parvizi</b>, Runnan Zou, Colin Bellinger, Ross Cheriton, Davide Spinello<br>
            <i>Photonics, vol. 10, no. 12, 2023 (MDPI)</i><br>
            <a href="https://www.mdpi.com/2304-6732/10/12/1371" target="_blank">Paper</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
            <a href="https://github.com/payamparvizi/adaptive_optics_gym" target="_blank">Code</a>
        </p>
    </div>
</div>
    <div class="list-item publication" data-category="publication">
        <a href="https://hal.science/hal-04605102/" class="thumbnail">
            <img src="/img/coat_t.png" alt="Wavefront Sensorless Adaptive Optics with Reinforcement Learning" />
        </a>
        <div class="project-description">
            <h3>
                <a href="https://hal.science/hal-04605102/" target="_blank">
                Wavefront Sensorless Adaptive Optics for Free-Space Satellite-to-Ground Communication Using Reinforcement Learning
                </a>
            </h3>
            <p>
                Runnan Zou, <b>Payam Parvizi</b>, Ross Cheriton, Colin Bellinger, Davide Spinello<br>
                <i>COAT 2023</i><br>
                <a href="https://hal.science/hal-04605102/" target="_blank">Paper</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
    <a href="https://open.metu.edu.tr/handle/11511/27117" class="thumbnail">
        <img src="/img/dmp_test_setup.png" alt="MSc Thesis: Robotic Deburring via Motion Primitives" />
    </a>
    <div class="project-description">
        <h3>
             <a href="https://open.metu.edu.tr/handle/11511/27117" target="_blank">
            Demonstration of Robotic Deburring Process Motor Skills from Motion Primitives of Human Skill Model
            </a>
        </h3>
        <p>
            <b>Payam Parvizi</b><br>
            <i>M.Sc. Thesis, Middle East Technical University (METU), 2018</i><br>
            <a href="https://open.metu.edu.tr/handle/11511/27117" target="_blank">M.Sc. Thesis</a>
        </p>
    </div>
</div>
    <div class="list-item publication" data-category="publication">
    <a href="https://ieeexplore.ieee.org/abstract/document/8266228" class="thumbnail" target="_blank">
        <img src="/img/1dof_dmp.png" alt="Teleoperation and Force Feedback in Precision Grinding" />
    </a>
    <div class="project-description">
        <h3>
            <a href="https://ieeexplore.ieee.org/abstract/document/8266228" target="_blank">
                Dynamic Movement Primitives and Force Feedback: Teleoperation in Precision Grinding Process
            </a>
        </h3>
        <p>
            Kemal Açıkgöz, <b>Payam Parvizi</b>, Abdulhamit Dönder, Musab Çağrı Uğurlu, Erhan İlhan Konukseven<br>
            <i>IEEE International Conference on Electrical and Electronics Engineering (ELECO), 2017</i><br>
            <a href="https://ieeexplore.ieee.org/abstract/document/8266228" target="_blank">Paper</a>
        </p>
    </div>
</div>
    <div class="list-item publication" data-category="publication">
        <a href="https://ieeexplore.ieee.org/abstract/document/8046856" class="thumbnail" target="_blank">
            <img src="/img/robotic-deburring.png" alt="Robotic Deburring via Motion Primitives" />
        </a>
        <div class="project-description">
            <h3>
                <a href="https://ieeexplore.ieee.org/abstract/document/8046856" target="_blank">
                    Parametrization of Robotic Deburring Process with Motor Skills from Motion Primitives of Human Skill Model
                </a>
            </h3>
            <p>
                <b>Payam Parvizi</b>, Musab Çağrı Uğurlu, Kemal Açıkgöz, Erhan İlhan Konukseven<br>
                <i>IEEE International Conference on Methods and Models in Automation and Robotics (MMAR), 2017</i><br>
                <a href="https://ieeexplore.ieee.org/abstract/document/8046856" target="_blank">Paper</a>
            </p>
        </div>
    </div>
    <!-- Talks -->
    <!-- Talks / Presentations -->
    <div class="list-item talk" data-category="talk">
      <p class="date">2025</p><b>Poster Presentation</b> — <a href="https://www.photonicsnorth.com/en" target="_blank">Photonics North</a> (Ottawa, Canada)
    </div>
    <div class="list-item talk" data-category="talk">
      <p class="date"></p><b>Seminar Talk</b> — MCG Seminars, Department of Mechanical Engineering, <a href="https://www.uottawa.ca/en" target="_blank">University of Ottawa</a>
    </div>
    <div class="list-item talk" data-category="talk">
      <p class="date">2023</p><b>Poster Presentation</b> — Technology for the Digital Transformation of Society, <a href="https://www.uottawa.ca/en" target="_blank">University of Ottawa</a>
    </div>
    <div class="list-item talk" data-category="talk">
      <p class="date"></p><b>Seminar Talk</b> — AI for Design Seminar, <a href="https://nrc.canada.ca/" target="_blank">National Research Council of Canada (NRC)</a>
    </div>
    <div class="list-item talk" data-category="talk">
      <p class="date"></p><b>Poster Presentation</b> — <a href="https://www.photonicsnorth.com/en" target="_blank">Photonics North</a> (Montreal, Canada)
    </div>
    <!-- -->
    <!-- Community Service -->
    <!-- -->
<!-- Experience -->
<div class="list-item experience" data-category="experience">
    <br>
    <h2>Work Experience</h2><br>
    <ul style="list-style-type: disc; margin-left: 1.5em;">
        <li style="margin-bottom: 0.75em;">
            <b>Research Associate</b>, <a href="https://www.uottawa.ca/en" target="_blank">University of Ottawa</a> (Nov. 2025 – Present)<br>
        </li>
        <li style="margin-bottom: 0.75em;">
            <b>Research Assistant</b>, <a href="https://www.uottawa.ca/en" target="_blank">University of Ottawa</a> & <a href="https://nrc.canada.ca/" target="_blank">NRC</a> (Apr. 2022 – Sept. 2025)<br>
        </li>
        <li style="margin-bottom: 0.75em;">
            <b>Teaching Assistant</b>, <a href="https://www.uottawa.ca/en" target="_blank">University of Ottawa</a> (Jan. 2019 – Apr. 2022)<br>
        </li>
        <li style="margin-bottom: 0.75em;">
            <b>Project Assistant</b>, <a href="https://www.metu.edu.tr/" target="_blank">Middle East Technical University</a> & <a href="https://tubitak.gov.tr/en" target="_blank">TÜBİTAK</a> (Nov. 2015 – Nov. 2017)<br>
        </li>
        <li style="margin-bottom: 0.75em;">
            <b>R&D Intern</b>, <a href="https://www.mercedesbenzturk.com.tr/" target="_blank">Mercedes-Benz Türk Inc.</a> (Jun. 2013 - Aug. 2013)<br>
        </li>
        <li style="margin-bottom: 0.75em;">
            <b>Maintenance Engineering Intern</b>, <a href="https://turkishtechnic.com/" target="_blank">Turkish Airlines Technic</a>  (Jan. 2012 - Mar. 2012)<br>
        </li>
    </ul>
    <h2>Education</h2><br>
    <ul style="list-style-type: disc; margin-left: 1.5em;">
        <li style="margin-bottom: 0.75em;">
            <b>Ph.D. in Mechanical Engineering</b>, <a href="https://www.uottawa.ca/en" target="_blank">University of Ottawa</a> (2025)<br>
        </li>
        <li style="margin-bottom: 0.75em;">
            <b>M.Sc. in Mechanical Engineering</b>, <a href="https://www.metu.edu.tr/" target="_blank">Middle East Technical University</a> (2018)<br>
        </li>
        <li style="margin-bottom: 0.75em;">
            <b>B.Sc. in Aerospace Engineering</b>, <a href="https://www.metu.edu.tr/" target="_blank">Middle East Technical University</a> (2014)<br>
        </li>
    </ul>
    <h2>Teaching Experience</h2><br>
    <ul style="list-style-type: disc; margin-left: 1.5em;">
        <li style="margin-bottom: 0.75em;"> MCG 3307: Control Systems (Winter 2019, 2020, 2021 & 2022) </li>
        <li style="margin-bottom: 0.75em;"> MCG 3306: System Dynamics (Fall 2020 & 2021) </li>
        <li style="margin-bottom: 0.75em;"> MCG 3305: Biomedical System Dynamics (Fall 2019) </li>
    </ul>
    <h2>Certifications</h2><br>
    <ul style="list-style-type: disc; margin-left: 1.5em;">
        <li style="margin-bottom: 0.75em;">
            <b>MITx MicroMasters</b> — Statistics and Data Science (2019 - 2020)
            <ul style="list-style-type: circle; margin-left: 1.5em; margin-top: 0.4em;">
                <li>Machine Learning with Python</li>
                <li>Fundamentals of Statistics</li>
                <li>Probability</li>
            </ul>
        </li>
    </ul>
</div>

</div>

<div id="footer">
    ©Payam Parvizi  | Design influenced by <a href="https://gauthamvasan.github.io/" target="_blank">Gautham Vasan</a>.
</div>

<script>
document.addEventListener('DOMContentLoaded', function() {
  var researchBtn = document.querySelector('button[data-filter=".research"]');
  if (researchBtn) {
    researchBtn.click();
  }
});
</script>


[RL-wiki]: https://en.wikipedia.org/wiki/Reinforcement_learning
