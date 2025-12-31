---
layout: page
title: Enhancing QR Code System Security by Verifying the Scanner's Gripping Hand Biometric
description: 
img: assets/img/wisec2024-figure-4.png
importance: 1
category: nsf1
related_publications: true
---

This work was published at ACM WiSec 2024 {% cite wang2024qrcode  %} and CHI 2022 Extended Abstracts {% cite wang2022kiosk  %}.

### Abstract

Because of the great convenience and being not readable to humans, Quick Response (QR) codes are increasingly being utilized
to offer a variety of security applications to mobile users, such as
online payments, website logins, and private data sharing. To facilitate these security applications, QR codes usually contain sensitive
information, such as bank account details, credit card numbers,
and personal/organizational/device data, or they are specifically
designed to work with cloud servers to provide security services.
However, there is currently no existing solution to verify the identity of the smartphone user who scans a QR code from a Kiosk or
another phone’s screen. Verifying the scanner’s identity is essential
to ensure that financial transactions go to the correct recipient and
that sensitive data is securely shared to its intended destination.
This work aims to equip QR code providers with the ability to
verify human scanners’ identities, facilitating authorization and
auditing. When a phone is held close to scan a QR code, we utilize
the front camera of the code provider (a Kiosk or phone) to simultaneously verify the scanner’s hand. Instead of requiring the scanner
to present a stretched palm to obtain traditional hand geometries,
we find that the geometry of an individual’s hand, when it grips a
phone, is also identifiable. We thus design a vision-based approach
to extract gripping hand biometrics. We leverage the QR code’s
screen to cast light onto the scanner’s gripping hand, ensuring
adequate illumination even in low-light conditions. We then use
a hand tracking tool, MediaPipe, to detect and localize the hand
and develop a transformer-based algorithm to verify four types of
gripping hand biometric features extracted from the hand image,
including hand contour, skeleton, color, and surface. We further
capture the subtle hand joint movements for liveness validation,
because the user needs to click touchscreen buttons to start QR
code scanning. Extensive experiments, including a long-term study
spanning over 32 months, show that the system achieves 98.3%
accuracy in verifying the user and mitigating 2D and 3D replay attacks. Compared to the widely used facial recognition, this approach addresses the recent struggles of identifying faces behind
masks and the public concerns about privacy erosion.
<br>
Keywords-QR code security, hand biometric, authentication

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/wisec2024-figure-1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Fig. 1: Enhanced QR code system security by verifying the scanner’s identity (illustrated with two typical scenarios)
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/wisec2024-figure-2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Fig. 2:Flow of the proposed QR code scanner authentication.
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/wisec2024-figure-3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Fig. 3:Transformer-based hand verification model.
</div>
