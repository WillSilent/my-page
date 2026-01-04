---
layout: page
title: Converting Your Bluetooth Headphones into Active Sensing Authenticator a Bone-Conduction Solution
description: 
img: assets/img/bond_conduction.jpg
importance: 3
related_publications: true
category: nsf2
---

This work was published at 2025 IEEE 22nd International Conference on Mobile Ad-Hoc and Smart Systems (MASS) {% cite zhang2025converting %}.

### Abstract

Bluetooth headphones are increasingly commonly used in daily life, offering convenience and enhanced audio experience. However, these devices remain underexplored for human-beneficial applications such as serving as authenticator due to the challenges of implementing acoustic sensing on them. Particularly, Bluetooth headphones are limited by low-frequency audio bandwidth and have built-in echo cancellation algorithms, which makes the recorded signal incomplete and cannot be used for acoustic analysis. This work addresses these challenges and achieves acoustic sensing on bone-conduction Bluetooth headphones to extract a unique bone-conducted head biometric for user authentication. Specifically, the proposed system emits a user-friendly signal consisting of a welcome tone followed by a short human voice, and analyzes the received signals using a convolutional neural network developed with residual blocks to derive stable biometrics to verify users. Extensive experiments show that the proposed system can verify users’ identities with an average accuracy of 97.51% and can successfully reject 100% of replay attacks, even when an adversary eavesdrops on the authentication sound and the acoustic biometric data.
<br>
Index Terms—Acoustic Sensing, User Authentication, Bluetooth Headphones, Bone-conducted Biometric

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bond_conduction_figure_1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Fig. 1: Illustrating of bone-conducted signal interacting with
the user’s head.
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bond_conduction_figure_2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
     Fig. 2: System architecture.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%;">
            <!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/8hNfBFUHFOA?si=0L2zPaEbczd8PCZ_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> -->
            <iframe
                src="https://www.youtube.com/embed/8hNfBFUHFOA?si=0L2zPaEbczd8PCZ_"
                style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"
                class="rounded z-depth-1"
                frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                allowfullscreen>
            </iframe>
            
        </div>
    </div>
</div>
<div class="caption">
    youtube-demo
</div>
