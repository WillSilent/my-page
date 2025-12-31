---
layout: page
title: Hand Skeleton Motion Behavior Verification
description: 
img: assets/img/ACSAC2023-figure-1.png
importance: 1
category: nsf1
related_publications: true
---

This work was published at Annual Computer Security Applications Conference(ACSAC 2023) {% cite deng2023signature %}.

### Abstract

Behavioral biometrics has emerged as an important security factorfor user authentication. Compared to static biometrics (e.g., faces,irises, and fingerprints), using human motion behaviors for authen-tication causes lower concern about privacy abuse, and behaviorbiometrics are shown hard to be replicated by humans. In-air 3D sig-nature is one representative of behavioral biometrics. Specifically, auser’s hand movements can be tracked by visual or wireless sensorsfor contact-free signature authentication, where both the fingertiptrajectory and the dynamic motion features are verified to provideenhanced security. However, with the advancement of 3D printingand robot technology, we find that 1: existing hand-tracking inter-faces (e.g., Leap Motion and Google MediaPipe) are easily trickedby a fake hand, and 2: a robotic arm can reproduce a user’s in-air3D signature with high similarity regarding both trajectory andmotion behaviors. Thus, this work investigates the security of in-airsignatures under robot-level replays and proposes to extend thesignature verification from a single-point fingertip to multiple handjoints for enhanced security. We develop the hand skeleton-based3D signature verification system, which can be deployed on anysingle camera devices (2D or 3D). The key insight is that currentrobots could hardly replicate the minute and unique inter-jointmotions of a user. In particular, we track the hand skeleton using asingle camera and reconstruct/draw the trajectories of its joints ina virtual 3D space, using the color gradients to represent time-lapseand using varying line widths to describe joint significance. Basedon that, we extract the three-view skeleton signatures and inter-joint motion features and develop a convolutional neural networkfor verification. Extensive experiments show that our system notonly achieves high authentication performance but also effectivelymitigates robot-level replay attacks.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/ACSAC2023-figure-1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Fig. 1: Vulnerability of current commodity hand-tracking
interfaces (easily fooled with a silicone fake hand).
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/ACSAC2023-figure-2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Fig. 2:The overview of our 3D hand skeleton signature user authentication system.
</div>


