---
layout: page
title: Sniffing Location Privacy of Video Conference Users Using Free Audio Channels
description: 
img: assets/img/sniff_location_figure_3.png
importance: 1
category: nsf2
related_publications: true
---

This work was published at IEEE Symposium on Security and Privacy 2024 {% cite wang2024sniffing %}.

## Abstract

Since the outbreak of the COVID-19 pandemic,
video conferencing apps have been more broadly used to
connect geographically distant people for work, school, and
social interactions. These apps simulate “in-person” meetings
with streamed audio and provide users with full control of
their privacy. For instance, users can conveniently disable
their microphones whenever they feel the need for privacy
following common senses: 1.Audio signals containing semantic or contextual information pose privacy concerns; 2. Microphones are relevant only to acoustic privacy; 3. Meeting
participants cannot actively intrude on each other’s privacy
but only opportunistically exploit accidental privacy leakages
or mistakes. This paper investigates the privacy leakages that
defy these assumptions. We find that any meeting participant
can actively and covertly probe others’ location privacy even
when the webcam is disabled or virtual backgrounds are used
to hide locations. More specifically, the legitimate two-way
audio channel of video conferencing facilitates remote acoustic
sensing, allowing an attacker to probe the users’ physical
surroundings and receive location-specific echo signals.
<br>
However, all video conferencing systems utilize echo cancellation functions to prevent audio feedback, which inherently
stops active sensing. To address this challenge, we develop
a transformer-based algorithm and leverage the encoders of
generative AI to counteract echo cancellation and extract stable location embeddings from severely distorted echo sounds.
Furthermore, we propose two types of active acoustic sensing
attacks: the in-channel echo attack, which breaks through echo
cancellation by using carefully crafted signals, and the offchannel echo attack, which exploits third-party media sounds
(e.g., email notification tones) to evade cancellation. We test
these attacks on commercial video conferencing apps, such as
Zoom, Teams, and Skype. When using only a single probing
sound, our methods achieve 88.3% accuracy in recognizing
recurrent places and 88.5% accuracy in identifying the contexts
of new (unseen or untagged) places.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/sniff_location_figure_1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Attacking scenario and echo sensing model.
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/sniff_location_figure_2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The flow of our location privacy inference system
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%;">
            <iframe
                src="https://www.youtube.com/embed/P8Hf7tLkTCg"
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