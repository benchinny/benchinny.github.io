---
layout: page
title: Temporal processing in the visual system
description: Probing how color signals in the visual system are combined across time
img: assets/img/colorfulClock.jpeg
importance: 2
category: work
---

Color signals in the human visual system are processed with different temporal latencies (delays) and integration periods. Notably, the short-wavelength-sensitive cone photoreceptors in the retina have longer latencies and integration periods than the long-wavelength-sensitive cones. During vision, both types of cones are modulated simultanously. How are their signals combined across time during motion? 

To address this question, we leverage a classic visual illusion, the Pulfrich effect. Using a device known as a haploscope, we present moving bars that have different colors between the left and right eyes to participants. These color differences between the eyes cause different processing latencies between the eyes. Because the bars are moving, the processing latencies create a binocular disparity signal, causing participants to misperceive the depth of the stimulus. 

<div class="row justify-content-sm-center">
    <div class="col-sm-12 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/PLSmainFig.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A) Different color signals are 'received' by the visual system at different times even when they originate from the same object. B) To make the diagram more realistic, we represent the fact that visual signals are not punctuate in time, but rather evolve over time. C) When each of a participant's eyes receives a moving bar stimulus with a different color, they may misperceive the depth of the bar due to different temporal processing between the eyes. 
</div>

From the magnitude of the Pulfrich effect, we inferred the processing delays and 'damping' due to temporal integration associated with different color stimuli. As the contrast of the S-cone modulation increases, both the delay and damping of the combined signal increase. 

<div class="row justify-content-sm-center">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/PLSdelays.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/PLSdamping.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Delay (left), and damping (right) as a function of contrast in the S-cone modulation of a stimulus composed of both L- and S-cone modulations. 
</div>

