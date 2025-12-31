---
layout: page
title: Fast Detection of Handheld Phone-distracted Driving by Sensing the Driver's Hand-grip
description: 
img: assets/img/TVT2024-figure-1.png
importance: 1
category: nsf1
related_publications: true
---

This work was published at IEEE Transactions on Vehicular Technology 2024 {% cite wang2024distracted %}.

### Abstract

This work proposes a media sound-based authentication method to protect smartphone notification privacy unobtrusively, which wisely hides or presents sensitive content by verifying who is holding the phone. We show that media sounds, such as the melodies of notification tones (e.g., iPhone message and Samsung whistle) can be directly used to sense and verify the user's gripping hand. Because sounds and vibrations co-exist, we capture two novel responses via the smartphone mic and accelerometer to describe how the individual's contacting palm interferes with the signals in two different domains. Based on the two responses, we develop a convolutional neural network-based algorithm to verify the user. Moreover, because the smartphone sensors are all embedded on the same motherboard, we develop a cross-domain method to validate such hard-to-forge physical relationships among the mic, speaker and accelerometer. They prevent external sounds from cheating the system. Additionally, we consider the notification vibration as a special type of media sound, which also results in two responses, and extend our method to work in the silent mode. Extensive experiments with ten notification tones and four phone models show that our system verifies users with 95% accuracy and prevents replay sounds with 100% accuracy.
<br>
Index Terms—Distracted driving, driver behavior, handheld device, vehicle safety.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/TVT2024-figure-1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Attacking scenario and echo sensing model.
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/TVT2024-figure-2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The flow of our location privacy inference system
</div>