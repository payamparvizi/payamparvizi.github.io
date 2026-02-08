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
    <br>
    <a href="#" onclick="event.preventDefault()" class="research-thumbnail">
        <img src="/img/quadcopter_poster.jpg" alt="Quadcopter RL Control" />
    </a>
    <div class="research-description">
        <h3>Reliable Reinforcement Learning for Continuous Control</h3>
        <p>
        I develop reinforcement learning methods for continuous-action systems with an emphasis on
        <b>smoothness, stability, and reliability</b>. My work focuses on action and policy regularization
        techniques to reduce high-frequency oscillations and improve deployment robustness in physical systems.
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
    <!-- -->
    <!-- Blog -->
    <!-- -->
    <div class="list-item blog" data-category="blog">
        <br>
        <h3> I write for fun/clarifying ideas for myself. My technical posts can be found below. 
        My personal blog is hosted at <a href="https://enlightenedidiot.net/" target="_blank" style="color: rgb(20, 110, 190);">enlightenedidiot.net</a> </h3>
        <br><br>
        <a href="/posts/2024-01-22-fun-with-vector-derivatives" class="thumbnail" target="_blank">
            <img src="https://wikimedia.org/api/rest_v1/media/math/render/svg/43b8c31f61f8b2bbe6f0df4d62012d8ba86ba420" alt="Blog Post Thumbnail">
        </a>
        <div class="project-description">
            <h2><a href="https://gauthamvasan.github.io/animated_clay/posts/fun-with-vector-derivatives/" target="_blank">Gradients, Jacobian and Fun With Vector Derivatives</a></h2>
        </div>
    </div>
    <div class="list-item blog" data-category="blog">
        <a href="https://gauthamvasan.github.io/img/moravec_paradox.png" class="thumbnail" target="_blank">
            <img src="/img/moravec_paradox.png" alt="Blog Post Thumbnail">
        </a>
        <div class="project-description">
            <h2><a href="https://gauthamvasan.github.io/animated_clay/posts/simulators-and-moravec-paradox/" target="_blank">Moravec's paradox, Sim-to-Real Transfer & Robot Learning</a></h2>
        </div>
    </div>
    <div class="list-item blog" data-category="blog">
        <a href="/posts/2020-08-06-resources-for-effective-research" class="thumbnail" target="_blank">
            <img src="https://upload.wikimedia.org/wikipedia/commons/3/39/Hamming.jpg" alt="Blog Post Thumbnail">
        </a>
        <div class="project-description">
            <h2><a href="https://gauthamvasan.github.io/animated_clay/posts/resources-for-effective-research/" target="_blank">Resources For Effective Research</a></h2>
        </div>
    </div>
    <div class="list-item blog" data-category="blog">
        <a href="/posts/2020-08-06-machinae-animatae" class="thumbnail" target="_blank">
            <img src="https://gauthamvasan.github.io/img/WallE_starry_night.jpg" alt="Blog Post Thumbnail">
        </a>
        <div class="project-description">
            <h2><a href="https://gauthamvasan.github.io/animated_clay/posts/machinae-animatae/" target="_blank">Machinae Animatae</a></h2>
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
        <a href="https://arxiv.org/abs/2410.14606" class="thumbnail" target="_blank">
             <img src="/img/streaming-deep-rl.png">
        </a>
        <div class="project-description">
            <h3><a href="https://arxiv.org/abs/2410.14606" target="_blank">Streaming Deep Reinforcement Learning Finally Works</a></h3>
            <p>
                Mohamed Elsayed, <b>Gautham Vasan</b>, A. Rupam Mahmood<br>
                <i>Pre-Print, NeurIPS FitML Workshop 2024</i><br>
                <a href="https://arxiv.org/abs/2410.14606" target="_blank">Paper</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://github.com/mohmdelsayed/streaming-drl" target="_blank">Code</a>
            </p>
        </div>
    </div>
     <div class="list-item publication" data-category="publication">
        <a href="https://arxiv.org/abs/2407.00324" class="thumbnail" target="_blank">
             <img src="/img/franka_reacher.jpg">
        </a>
        <div class="project-description">
            <h3><a href="https://arxiv.org/abs/2407.00324" target="_blank">Revisiting Sparse Rewards for Goal-Reaching Reinforcement Learning</a></h3>
            <p>
                <b>Gautham Vasan</b>, Yan Wang, Fahim Shahriar, James Bergstra, Martin Jagersand, A. Rupam Mahmood<br>
                <i>RLC 2024</i><br>
                <a href="https://arxiv.org/abs/2407.00324" target="_blank">Paper</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://youtu.be/a6zlVUuKzBc" target="_blank">Demo</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://github.com/gauthamvasan/rl_suite" target="_blank">Code</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="https://openreview.net/pdf?id=TgXIkK8WPQ" class="thumbnail" target="_blank">
             <img src="/img/RL_Chemist_Setup.jpg">
        </a>
        <div class="project-description">
            <h3><a href="https://openreview.net/pdf?id=TgXIkK8WPQ" target="_blank">Versatile and Generalizable Manipulation via Goal-Conditioned Reinforcement Learning with Grounded Object Detection</a></h3>
            <p>
                Huiyi Wang, Fahim Shahriar, Alireza Azimi, <b>Gautham Vasan</b>, A. Rupam Mahmood, Colin Bellinger<br>
                <i>CoRL MRM-D Workshop 2024</i><br>
                <a href="https://openreview.net/pdf?id=TgXIkK8WPQ" target="_blank">Paper</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="https://www.ifaamas.org/Proceedings/aamas2024/pdfs/p2785.pdf" class="thumbnail" target="_blank">
             <img src="/img/vector_charger_detector.jpg">
        </a>
        <div class="project-description">
            <h3><a href="https://www.ifaamas.org/Proceedings/aamas2024/pdfs/p2785.pdf" target="_blank">Autonomous Skill Acquisition for Robots Using Graduated Learning</a></h3>
            <p>
                <b>Gautham Vasan</b><br>
                <i>AAMAS Doctoral Consortium 2024</i><br>
                <a href="https://www.ifaamas.org/Proceedings/aamas2024/pdfs/p2785.pdf" target="_blank">Paper</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="https://arxiv.org/abs/2312.15339" class="thumbnail" target="_blank">
             <img src="/img/madi_setup.jpg">
        </a>
        <div class="project-description">
            <h3><a href="https://arxiv.org/abs/2312.15339" target="_blank">MaDi: Learning to Mask Distractions for Generalization in Visual Deep Reinforcement Learning</a></h3>
            <p>
                Bram Grooten, Tristan Tomilin, <b>Gautham Vasan</b>, Matthew E Taylor, A Rupam Mahmood, Meng Fang, Mykola Pechenizkiy, Decebal Constantin Mocanu<br>
                <i>AAMAS 2024</i><br>
                <a href="https://arxiv.org/abs/2312.15339" target="_blank">Paper</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://youtu.be/2oImF0h1k48" target="_blank">Video</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="https://proceedings.mlr.press/v202/che23c.html" class="thumbnail" target="_blank">
             <img src="/img/discount_correction.jpg">
        </a>
        <div class="project-description">
            <h3><a href="https://proceedings.mlr.press/v202/che23c.html" target="_blank">Correcting Discount-Factor Mismatch in On-Policy Policy Gradient Methods</a></h3>
            <p>
                Fengdi Che, <b>Gautham Vasan</b>, A. Rupam Mahmood<br>
                <i>ICML 2023</i><br>
                <a href="https://proceedings.mlr.press/v202/che23c.html" target="_blank">Paper</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="https://arxiv.org/abs/2210.02317" class="thumbnail" target="_blank">
             <img src="/img/relod.jpg">
        </a>
        <div class="project-description">
            <h3><a href="https://arxiv.org/abs/2210.02317" target="_blank">Real-Time Reinforcement Learning for Vision-Based Robotics Utilizing Local and Remote Computers</a></h3>
            <p>
                Yan Wang*, <b>Gautham Vasan*</b>, A. Rupam Mahmood<br>
                <i>ICRA 2023</i><br>
                <a href="https://arxiv.org/abs/2210.02317" target="_blank">Paper</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://youtu.be/7iZKryi1xSY" target="_blank">Video</a>
            </p>
        </div>
    </div>  
    <div class="list-item publication" data-category="publication">
        <a href="https://arxiv.org/abs/1903.11524" class="thumbnail" target="_blank">
            <img src="/img/ARP/ARP_Blog3.png" alt="ARP Blog3" />
        </a>
        <div class="project-description">
            <h3><a href="https://arxiv.org/abs/1903.11524" target="_blank">Autoregressive policies for continuous control deep reinforcement learning</a></h3>
            <p>
                Dmytro Korenkevych, A Rupam Mahmood, <b>Gautham Vasan</b>, James Bergstra<br>
                <i>IJCAI 2019</i><br>
                <a href="https://arxiv.org/abs/1903.11524" target="_blank">Paper</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://www.kindred.ai/blog/introducing-autoregressive-policies-for-temporally-coherent-exploration-in-continuous-control-reinforcement-learning" target="_blank">Post</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://youtu.be/NCpyXBNqNmw" target="_blank">Video</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="https://arxiv.org/abs/1809.07731" class="thumbnail" target="_blank">
            <img src="/img/SenseAct/ur-reacher-2-trpo.gif" alt="UR-Reacher-2" />
        </a>
        <div class="project-description">
            <h3><a href="https://arxiv.org/abs/1809.07731" target="_blank">Benchmarking reinforcement learning algorithms on real-world robots</a></h3>
            <p>
                A Rupam Mahmood, Dmytro Korenkevych, <b>Gautham Vasan</b>, William Ma, James Bergstra<br>
                <i>CoRL 2018</i><br>
                <a href="https://arxiv.org/abs/1809.07731" target="_blank">Paper</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://www.kindred.ai/blog/benchmarking-reinforcement-learning-algorithms-on-real-world-robots" target="_blank">Post</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://youtu.be/ovDfhvjpQd8" target="_blank">Video</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://www.kindred.ai/blog/introducing-a-framework-and-benchmark-tasks-for-reproducible-reinforcement-learning-research-on-real-robots" target="_blank">SenseAct</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="https://sites.ualberta.ca/~pilarski/docs/papers/Vasan_2018_BioRob_preprint.pdf" class="thumbnail" target="_blank">
            <img src="/img/BioRob_2018/contextual_lfd_trial.jpg" alt="Contextual LfD Trial" />
        </a>
        <div class="project-description">
            <h3><a href="https://sites.ualberta.ca/~pilarski/docs/papers/Vasan_2018_BioRob_preprint.pdf" target="_blank">Context-Aware Learning from Demonstration: Using Camera Data to Support the Synergistic Control of a Multi-Joint Prosthetic Arm</a></h3>
            <p>
                <b>Gautham Vasan</b>, Patrick M Pilarski<br>
                <i>BioRob 2018</i><br>
                <a href="https://sites.ualberta.ca/~pilarski/docs/papers/Vasan_2018_BioRob_preprint.pdf" target="_blank">Paper</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://docs.google.com/presentation/d/1gKY5LgBuBRYCs3NW5iyfrGNq6xCAxeg3zoM00j9C_Sw/edit?usp=sharing" target="_blank">Poster</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="https://sites.ualberta.ca/~pilarski/docs/papers/Vasan_2017_ICORR_preprint.pdf" class="thumbnail" target="_blank">
            <img src="/img/ICORR_2017/Lfd_amputee.png" alt="LfD Amputee" />
        </a>
        <div class="project-description">
            <h3><a href="https://sites.ualberta.ca/~pilarski/docs/papers/Vasan_2017_ICORR_preprint.pdf" target="_blank">Learning from demonstration: Teaching a myoelectric prosthesis with an intact limb via reinforcement learning</a></h3>
            <p>
                <b>Gautham Vasan</b>, Patrick M Pilarski<br>
                <i>ICORR 2017</i><br>
                Spotlight presentation at Rehabweek 2017.<br>
                <a href="https://sites.ualberta.ca/~pilarski/docs/papers/Vasan_2017_ICORR_preprint.pdf" target="_blank">Paper</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://docs.google.com/drive/folders/0B8-iXsaYqsxmUWJnTkpvMkplMXM?usp=sharing" target="_blank">Video & Metadata</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="#" class="thumbnail">
            <img src="/img/ICORR_2017/bentoarm.jpg" alt="Bento Arm" />
        </a>
        <div class="project-description">
            <h3><a href="#">Mirrored Bilateral Training of a Myoelectric Prosthesis with a non-amputated arm via Actor-Critic Reinforcement Learning</a></h3>
            <p>
                <b>Gautham Vasan</b>, Patrick M Pilarski<br>
                <i>RLDM 2017</i><br>
                Spotlight presentation (20min)<br>
                <a href="https://docs.google.com/presentation/d/1xd4nhI-4XbSqV0v_7MCv3qOl5pUkkaOPfkQobLNZlL0/edit?usp=sharing" target="_blank">Poster</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://docs.google.com/presentation/d/1H19Mm8-aJNWyDSRAB-bmE11M29-23pB_zIlH72iSkQA/edit?usp=sharing" target="_blank">Slides</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="https://arxiv.org/pdf/1604.07097.pdf" class="thumbnail" target="_blank">
            <img src="/img/NeuroHex/hexboard.png" alt="NeuroHex Board" />
        </a>
        <div class="project-description">
            <h3><a href="https://arxiv.org/pdf/1604.07097.pdf" target="_blank">Neurohex: A Deep Q-Learning Hex Agent</a></h3>
            <p>
                Kenny Young, <b>Gautham Vasan</b>, Ryan Hayward<br>
                <i>Computer Games Workshop at IJCAI 2016</i><br>
                <a href="https://arxiv.org/pdf/1604.07097.pdf" target="_blank">Paper</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="https://ieeexplore.ieee.org/abstract/document/7414792" class="thumbnail" target="_blank">
            <img src="/img/ardrone.jpg" alt="Quadrotor" />
        </a>
        <div class="project-description">
            <h3><a href="https://ieeexplore.ieee.org/abstract/document/7414792" target="_blank">Autonomous Visual Tracking and Landing of a Quadrotor on a Moving Platform</a></h3>
            <p>
                Juhi Ajmera, PR Siddharthan, KM Ramaravind, <b>Gautham Vasan</b>, Naresh Balaji, V Sankaranarayanan<br>
                <i>IEEE ICIIP 2015</i><br>
                <a href="https://ieeexplore.ieee.org/abstract/document/7414792" target="_blank">Paper</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://drive.google.com/file/d/0B78EAxFuk2RLWUsyOWdTMTdYak0/view?usp=sharing" target="_blank">Video</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="https://arxiv.org/abs/1412.0591" class="thumbnail" target="_blank">
            <img src="/img/TI/robot_1.png" alt="TI Robot 1" />
        </a>
        <div class="project-description">
            <h3><a href="https://arxiv.org/abs/1412.0591" target="_blank">A Control Strategy for an Autonomous Robotic Vacuum Cleaner for Solar Panels</a></h3>
            <p>
                <b>Gautham Vasan</b>, G Aravind, TSB Gowtham Kumar, R Naresh Balaji, G Saravana Ilango<br>
                <i>IEEE Texas Instruments India Educators Conference 2014</i><br>
                Phase-I Winners and finalists (top 19 among 2000+ teams)<br>
                <a href="https://arxiv.org/abs/1412.0591" target="_blank">Paper</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://youtu.be/qiCRSVuftFQ" target="_blank">Video</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://youtu.be/B_-TnMiD76M" target="_blank">Presentation</a>
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
