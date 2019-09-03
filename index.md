---
title: Home
layout: default
image_sliders:
  - recent_updates
---

[comment]: <> (Adding/Removing News Stories from the Carousel.)
[comment]: <> (1. Make sure your images are at a resolution of 660px by 260px.)
[comment]: <> (2. Add your images in /assets/img/carousel)
[comment]: <> (3. In /_data/sliders.yml, this is where all Carousel items are stored in the order they appear)
[comment]: <> (4. The spacing must be formatted exactly how the file currently is in regards to spacing.)
[comment]: <> (5. The src: attribute refers to the location your image is located and named.)
[comment]: <> (6. The alt: attribute refers to what text will be displayed onscreen on your image.)
[comment]: <> (7. The href: attribute refers to where the image will redirect you to Be Sure it is HTTPS.)
[comment]: <> (8. Make sure the Adapt Logo ends the carousel.)
[comment]: <> (9. You can add and delete, as the carousel will each time pull from the specified order.)

{% include slider.html selector="recent_updates" %}

<br>

## Adapt Research Projects

* ### [Memory Benchmarking](https://github.com/BoiseState-AdaptLab/AdaptMemBench)
* ### Automated Code Translation
* ### [Full Waveform Lidar Data Processing](https://github.com/BoiseState-AdaptLab/adapt-lidar-tools)
* ### [Polyhedral Dataflow IR](https://github.com/CompOpt4Apps/VariationsOnATheme)