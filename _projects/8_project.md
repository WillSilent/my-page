---
layout: page
title: Project2
description: Low-effort VR Headset User Authentication Using Head-reverberated Sounds with Replay Resistance
img: assets/img/Low-effort_VR_figure_1.png
importance: 2
related_publications: true
category: nsf2
---

This work was published at IEEE Symposium on Security and Privacy 2023 {% cite wang2023loweffort %}.

## Abstract

While Virtual Reality (VR) applications are becoming increasingly common, efficiently verifying a VR device user
before granting personal access is still a challenge. Existing VR
authentication methods require users to enter PINs or draw
graphical passwords using controllers. Though the entry is in
the virtual space, it can be observed by others in proximity and
is subject to critical security issues. Furthermore, the in-air hand
movements or handheld controller-based authentications require
active user participation and are not time-efficient. This work
proposes a low-effort VR device authentication system based on
the unique skull-reverberated sounds, which can be acquired
when the user wears the VR device. Specifically, when the user
puts on the VR device or is wearing it to log into an online
account, the proposed system actively emits an ultrasonic signal
to initiate the authentication session. The signal returning to the
VR device’s microphone has been reverberated by the user’s
head, which is unique in size, skull shape and mass. We thus
extract head biometric information from the received signal for
unobtrusive VR device authentication.
<br>
Though active acoustic sensing has been broadly used on
mobile devices, no prior work has ever successfully applied
such techniques to commodity VR devices. Because VR devices
are designed to provide users with virtual reality immersion,
the echo sounds used for active sensing are unwanted and
severely suppressed. The raw audio before this process is also
not accessible without kernel/hardware modifications. Thus, our
work further solves the challenge of active acoustic sensing under
echo cancellation to enable deploying our system on off-the-shelf
VR devices. Additionally, we show that the echo cancellation
mechanism is naturally good to prevent acoustic replay attacks.
The proposed system is developed based on an autoencoder and
a convolutional neural network for biometric data extraction and
recognition. Experiments with a standalone and a mobile phone
VR headset show that our system efficiently verifies a user and
is also replay-resistant.
<br>
Index Terms—Virtual Reality, Authentication, Biometric

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        <div>
            {% include figure.liquid loading="eager" path="assets/img/Low-effort_VR_figure_2.png" title="example image" class="img-fluid rounded z-depth-1" style="height: 200px;"%}
            <div class="caption">
                 The architecture of our system.
            </div>
        </div>
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Low-effort_VR_figure_3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Detailed design of our CAE-CNN algorithm.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%;">
            <iframe
                src="https://www.youtube.com/embed/fda20SS_M_Q"
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