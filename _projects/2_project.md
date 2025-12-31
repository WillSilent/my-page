---
layout: page
title: Low-effort Handheld Device User Authentication Using Musical Sounds
description: 
img: assets/img/mobicom2021-figure-1.png
importance: 1
category: nsf1
related_publications: true
---

This work was published at IEEE Internet of Things Journal 2025 {% cite huang2025musical %} and The 27th Annual International Conference On Mobile Computing And Networking (ACM MOBICOM 2021), {% cite huang2021notification  %}.

### Abstract

This work proposes a media sound-based authentication method to protect smartphone notification privacy unobtrusively, which wisely hides or presents sensitive content by verifying who is holding the phone. We show that media sounds, such as the melodies of notification tones (e.g., iPhone message and Samsung whistle) can be directly used to sense and verify the user's gripping hand. Because sounds and vibrations co-exist, we capture two novel responses via the smartphone mic and accelerometer to describe how the individual's contacting palm interferes with the signals in two different domains. Based on the two responses, we develop a convolutional neural network-based algorithm to verify the user. Moreover, because the smartphone sensors are all embedded on the same motherboard, we develop a cross-domain method to validate such hard-to-forge physical relationships among the mic, speaker and accelerometer. They prevent external sounds from cheating the system. Additionally, we consider the notification vibration as a special type of media sound, which also results in two responses, and extend our method to work in the silent mode. Extensive experiments with ten notification tones and four phone models show that our system verifies users with 95% accuracy and prevents replay sounds with 100% accuracy.
<br>
Key Words—Notification Privacy, User Authentication, Gripping Hand.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/mobicom2021-figure-1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Attacking scenario and echo sensing model.
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/mobicom2021-figure-2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The flow of our location privacy inference system
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%;">
            <iframe
                src="https://www.youtube.com/embed/O27qHI4KLEE"
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
