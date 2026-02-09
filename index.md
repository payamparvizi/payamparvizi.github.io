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
    <button class="button" data-filter=".service">Service</button>
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
        <br>
        <a href="https://openreview.net/forum?id=DX5GUwMFFb" class="thumbnail" target="_blank">
            <img src="/img/AVG_thumbnail.png" alt="AVG paper thumbnail" />
        </a>
        <div class="project-description">
            <h3><a href="https://arxiv.org/pdf/2411.15370" target="_blank">Deep Policy Gradient Methods Without Batch Updates, Target Networks, or Replay Buffers</a></h3>
            <p>
                <b>Gautham Vasan</b>, Mohamed Elsayed, Alireza Azimi, Jiamin He, Fahim Shahriar, Colin Bellinger, Martha White, A. Rupam Mahmood<br>
                <i>NeurIPS 2024</i><br>
                <a href="https://arxiv.org/pdf/2411.15370" target="_blank">Paper</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://github.com/gauthamvasan/avg" target="_blank">Code</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://colab.research.google.com/drive/1j4ONR062WQ_Fqs0yt07uBdm9zz7HGbte?usp=sharing" target="_blank">Colab</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://youtu.be/cwwuN6Hyew0" target="_blank">Video Demo</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://www.youtube.com/watch?v=mQc4ETehniI" target="_blank">Cohere4AI Talk</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="#" class="thumbnail">
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
    <a href="#" class="thumbnail">
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
    <a href="https://ieeexplore.ieee.org/search/searchresult.jsp?queryText=Dynamic%20movement%20primitives%20and%20force%20feedback%3A%20Teleoperation%20in%20precision%20grinding%20process" class="thumbnail" target="_blank">
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
        <a href="https://ieeexplore.ieee.org/search/searchresult.jsp?queryText=Parametrization%20of%20robotic%20deburring%20process%20with%20motor%20skills%20from%20motion%20primitives%20of%20human%20skill%20model" class="thumbnail" target="_blank">
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
    <!-- -->
<div class="talks-grid">
      <div class="list-item talk" data-category="talk">
        <h3 style="margin-top:0;"><b>Deep Policy Gradient Methods Without Batch Updates, Target Networks, or Replay Buffers</b></h3>
        <iframe width="100%" height="315" src="https://www.youtube.com/embed/mQc4ETehniI?si=xG6ZJeOiRRymrDiv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen style="margin-top:1em;"></iframe>
      </div>
      <div class="list-item talk" data-category="talk">
        <h3 style="margin-top:0;"><b>Two Issues of Autonomous Robot Learning</b></h3>
        <iframe width="100%" height="315" src="https://www.youtube.com/embed/QO0mmHMJvRQ?si=KGif_tvrkIN06zo0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen style="margin-top:1em;"></iframe>
      </div>
      <div class="list-item talk" data-category="talk">
        <h3 style="margin-top:0;"><b>Reward (Mis-)Specification in Reinforcement Learning</b></h3>
        <iframe width="100%" height="315" src="https://www.youtube.com/embed/yqeiXpbDoKg?si=NuWSQoWizPiLL8Ic&amp;start=517" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen style="margin-top:1em;"></iframe>
      </div>
      <div class="list-item talk" data-category="talk">
        <h3 style="margin-top:0;"><b>natChat: Neurotech in Artificial Intelligence (2023)</b></h3>
        <iframe width="100%" height="315" src="https://www.youtube.com/embed/kkJ8-k-_CPQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen style="margin-top:1em;"></iframe>
      </div>
    </div>
    <!-- -->
    <!-- Community Service -->
    <!-- -->
    <div class="list-item service" data-category="service">
        <br>
        <h2>Professional Activities</h2><br>
        <ul style="list-style-type: disc; margin-left: 1.5em;">
            <li style="margin-bottom: 0.75em;">Workflow Chair for AAAI 2026 </li>
            <li style="margin-bottom: 0.75em;">Reviewer: ICML, RLC, Collas, ICLR, NeurIPS,  BioRob, ICORR, ICDL, IROS </li>
            <li style="margin-bottom: 0.75em;"> Candidate selection for the CIFAR Deep Learning and Reinforcement Learning Summer School 2023 & 2024 </li>
            <li style="margin-bottom: 0.75em;"> Mentoring: Six students at the University of Alberta (undergraduate and masters level) on robot learning research </li>
        </ul>
        <h2>Community Service</h2><br>
        <ul style="list-style-type: disc; margin-left: 1.5em;">
            <li style="margin-bottom: 0.75em;">Research volunteer with The Hospital for Sick Children (<a href="https://www.sickkids.ca/" target="_blank">SickKids</a>, 2019)</li>
            <li style="margin-bottom: 0.75em;">Cerebral Palsy and Spasticity Trials: Worked with doctors on a study assessing functional gain in patients affected by stroke or spasticity using assistive robots.</li>
        </ul>
        <h2>Teaching Experience</h2><br>
        <ul style="list-style-type: disc; margin-left: 1.5em;">
            <li style="margin-bottom: 0.75em;"> CMPUT 340: Introduction to Numerical Methods (Winter 2024) </li>
            <li style="margin-bottom: 0.75em;"> CMPUT 653: Real-Time Policy Learning (Fall 2023) </li>
            <li style="margin-bottom: 0.75em;"> CMPUT 365: An Introduction to Reinforcement Learning (Winter 2021, Winter 2022, Fall 2022) </li>
            <li style="margin-bottom: 0.75em;"> CMPUT 174: Introduction to the Foundations of Computation I (Fall 2015, Winter 2016, Fall 2020) </li>
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
