---
layout: page
title: Centipede-Inspired Robotics
description: ...pushing the limits of...
img: assets/img/juntao_paper.gif
importance: 1
#category: work
related_publications: false
---

Most robotics efforts nowadays go towards the development of extremely complex algorithms for enhancing locomotion on complex terrains, relying on the so-called computational intelligence. However, such algorithms are highly dependent on vision capabilities, which are often not available in cluttered, dark, narrow environments like search-and-rescue environments are. For this reason, in our lab, our objective is to take advantage of our robot's mechanical intelligence in order to perform complex locomotion tasks even just using open-loop control systems, which then coupled with simpler algorithms can achieve high-quality results on all terrains.

By definition, centipede robots are long and narrow. The first feature, combined with their spatial redundancy (multiple legs) allows for great stability on every terrain. The second feature allows them to reach environments that most other legged robot cannot. The addition of bio-inspired compliance, bio-inspired tactile sensing, clever closed-loop/learning-based control systems then allows to optimize their performances.

<br>

<div class="row justify-content-sm-center">
    <div class="col-sm-6 d-flex align-items-stretch mt-3 mt-md-0">
        <img src="{{ '/assets/img/riproviamo.jpg' | relative_url }}" alt="example image" class="img-fluid rounded w-100" style="object-fit: contain; height: 300px;">
    </div>
    <div class="col-sm-6 d-flex align-items-stretch mt-3 mt-md-0">
        <img src="{{ '/assets/img/outdoor.png' | relative_url }}" alt="example image" class="img-fluid rounded w-100" style="object-fit: contain; height: 300px;">
    </div>
</div>


<div class="caption">
    Left picture shows the robot locomoting through cluttered environments, both artificial and natural, displaying the system's climbing and unjamming capabilities. On the right a timelapse of the robot locomoting through a cluttered pipe, displaying the system's ability to locomote through narrow environments.
</div>

<br>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <video width="100%" controls>
            <source src="https://www.dropbox.com/scl/fi/k1o1g3s37crsp3nkjpwoh/SI_High_Resulution-1.mp4?rlkey=852cuc7utveasx5ifp15ehuvp&st=upo1o4g6&dl=1" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>
</div>

<div class="caption">
    The video above is the SI video of our latest RSS submission
</div>

<br>

The work presented above rapresents only the first step of a larger series. Future work, in collaboration with the PhD student Juntao He, will involve the design of improved tactile sensing mechanisms, the creation of a learning-based controller, and SLAM applications.

