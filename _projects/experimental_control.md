---
layout: page
title: Experiment automation and control
description: Greiner lab, Harvard University
img: assets/img/experiment_control.png
importance: 1
category: computing
---

<!-- Add ml and mr add left and right margins -->
<div class="row">
    <div class="col-sm mt-3 ml-5 mr-5 mt-md-0">
        <img class="img-fluid z-depth-1 rounded" src="/assets/img/experiment_control.png" title="Experiment control diagram">
    </div>
</div>
<div class="caption">
    
</div>

One of my goals while working on the experimental system at Harvard University was to make sure the experiment was running smoothly and to automate common tasks that were needed to calibrate the experiment. To that end, I have led integration between different existing experimental systems, such as the custom experiment control system written in C# and the Python data analysis suite.

I built a python package which allows for easy scheduling of experimental sequences, automated data analysis and feedback on experimental parameters. By using an external experiment optimization package (M-LOOP), now it is possible to automatically optimize several experimental parameters at once. These upgrades have reduced the need for manual optimization of the experiment, enabling the experimenter to focus on other tasks. The uptime of the experiment has been increased, enabling automatic running of the experiment over nights or the weekends, with automatic recalibration of experimental parameters. To track the lab parameters while the experiment is running, I improved the lab’s data logging system by collecting all the relevant data (like lab temperatures) into a single, easy-to-use Grafana dashboard. 
