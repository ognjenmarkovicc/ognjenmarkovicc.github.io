---
layout: page
title: Grover algorithm proposal
description: Schleier-Smith lab, Stanford University, 2020-2021
img: assets/img/thumbnails/grover_proposal_small.png
importance: 3
category: research
---

<!-- Add ml and mr add left and right margins -->
<div class="row">
    <div class="col-sm mt-md-0">
    </div>
    <div class="col-sm mt-md-0">
        <img class="img-fluid z-depth-1 rounded" src="/assets/img/grover_proposal.png" title="Grover algorithm proposal teaser">
    </div>
    <div class="col-sm mt-md-0">
    </div>
</div>
<div class="caption">
    
</div>

The focus of quantum computing research is increasingly on finding useful algorithms that can be performed on near-term quantum machines. One such algorithm is Grover’s algorithm, which enables a speedup in searching through an unsorted database of items as compared to classical search algorithms. In this project, we proposed a hardware-efficient implementation of Grover’s algorithm in near-term quantum platforms which can be used to solve the number partitioning problem. 

My focus in this work was in finding the realistic experimental parameters where this algorithm can be implemented while still attaining a speedup compared to an equivalent classical algorithm. I developed a way to estimate sources of noise naturally present in these systems, and ran simulations to numerically optimize the algorithm speedup when varying algorithm parameters. In this work, we showed that it is possible to implement Grover’s algorithm to solve the number partitioning problem in near-term devices with a speedup under realistic experimental parameters.