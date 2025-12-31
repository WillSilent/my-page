---
layout: page
title: Biometric Encoding for Replay-Resistant Smartphone User Authentication Using Handgrips
description: 
img: assets/img/PCR-auth-figure-1.png
importance: 1
category: nsf1
related_publications: true
---

This work was published at IEEE Transactions on Mobile Computing 2025 {% cite huang2025biometric %} and IEEE Symposium on Security and Privacy 2022 {% cite huang2022pcr %}.

### Abstract

Biometrics have been widely applied for user authentication. However, existing biometric authentications are vulnerable to biometric spoofing, because they can be observed and forged.
In addition, they rely on verifying biometric features that rarely
change. To address this issue, we propose to verify the handgrip
biometric that can be unobtrusively extracted by acoustic signals
when the user holds the phone. This biometric is uniquely associated with the user’s hand geometry, body-fat ratio, and gripping
strength, which are hard to reproduce. Furthermore, we propose
two biometric encoding techniques (i.e., temporal-frequential and
spatial) to convert static biometrics into dynamic biometric features
to prevent data reuse. In particular, we develop a biometric authentication system to work with the challenge-response protocol.
We encode the ultrasonic signal according to a random challenge
sequence and extract a distinct biometric code as the response. We
further develop two decoding algorithms to decode the biometric
code for user authentication. Additionally, we investigate multiple
new attacks and explore using a latent diffusion model to solve the
acoustic noise discrepancies between the training and testing data
to improve system performance. Extensive experiments show our
system achieves 97% accuracy in distinguishing users and rejects
100% replay attacks with 0.6 s challenge sequence.
<br>
Index Terms—Challenge response, handgrip biometrics, replay
resistance, user authentication.



<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/PCR-auth-figure-2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Fig. 1:Our challenge-response authentication model.
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/PCR-auth-figure-3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Fig. 1:The architecture of PCR-Auth.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%;">
            <iframe
                src="https://www.youtube.com/embed/gUcs_MlIMLo"
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