---
title       : Sedimentation of active particles
subtitle    : Orientation distribution of active particles
author      : Katrin Wolff
job         : phys
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## What are active particles?

- Active particles are micron-sized particles using chemical energy to
  achieve propulsion
- Here, we have a look at self-propelled particles (for simulations this
 just means that they have fixed intrinsic speed $v_0$ but variable orientation
 $\mathbf{p}$)
- Particles could, for example, be microswimmers like bacteria or catalytic
 (and therefore self-propelled) colloids

<div style='text-align: center;'>
<img src="fig/activeparticle.jpg" style="width: 200px;"/>
</div>

---&twocol w1:40% w2:60%

## Sedimentation profile

*** =right

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png) 

*** =left

Simulation snapshot of active sedimenting particles

<img src="fig/snapshotpe8thinnedout.png" style="width: 300px;"/>

Sedimentation profile is similar to that of passive particles and an effective 
temperature $T_\mathrm{eff}$ depending on particle speed can be defined.

---&twocol w1:40% w2:60%

## Uniform orientation distribution overall

*** =left

![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2-1.png) 

*** =right

- No aligning force (torque) acting on particles $\hookrightarrow$ overall
    distribution of particles is uniform
    
- $z$-component of orientation is $p_z = \cos(\theta) \in [-1,1]$ where $-1$
    means "swimming down" and $+1$ means "swimming up".

---&twocol w1:30% w2:30%


However, if we restrict our data to certain position slices (see illustration
on p. 3), particles do have preferred swimming directions! 
This is purely a kinetic "sorting" effect without counterpart for equilibrium
systems and passive particles.

*** =left

![plot of chunk unnamed-chunk-3](assets/fig/unnamed-chunk-3-1.png) 

*** =right

![plot of chunk unnamed-chunk-4](assets/fig/unnamed-chunk-4-1.png) 




