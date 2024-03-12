---
layout: single
title: "Code"
permalink: /code/
author_profile: true
---

{% include base_path %}

## Emulating Ecological Memory with Recurrent Neural Networks

[Code](https://github.com/bask0/dl4es_ch18) on github

With [Basil Kraft](https://scholar.google.de/citations?user=SsP9UzQAAAAJ&hl=en) and [Sujan Koirala](https://www.bgc-jena.mpg.de/person/skoirala/4680511), we developped an deep learning emulator to provide an insight into the relevance of memory effects in the Earth system and presents an experimental case study to use an Recurrent Neural Network (RNN) model to emulate a physical model. We demonstrate that an RNN is largely capable of learning the memory effects encoded in a physical model. A non-temporal fully connected model cannot reproduce such memory effects, especially during anomalous conditions (e.g. climate extremes).

{::options parse_block_html="true" /}
<details>

If using this code, please cite: **Emulating Ecological Memory with Recurrent Neural Networks** _B. Kraft, S. Besnard, S. Koirala_ [Deep Learning for the Earth Sciences: A Comprehensive Approach to Remote Sensing, Climate Science and Geosciences](https://doi.org/10.1002/9781119646181.ch18), Nov. 2019.

```
@incollection{Kraft2021emulating,
    title = {Emulating Ecological Memory with Recurrent Neural Networks},
    booktitle = {Deep Learning for the Earth Sciences: A Comprehensive Approach to Remote Sensing, Climate Science and Geosciences},
    author = {Kraft, Basil and Besnard, Simon and Koirala, Sujan},
    editor = {Camps-Valls, Gustau and Tuia, Devis and Zhu, Xiao Xiang and Reichstein, Markus},
    edition = {1st edition},
    publisher = {{Wiley \& Sons}},
    isbn = {978-1-119-64614-3},
    Year = {2021}
}
```

</details>

{::options parse_block_html="false" /}

## A Python package for model training and upscaling forest age product

[ageUpscaling code](https://git.gfz-potsdam.de/global-land-monitoring/forest-age-upscale)

The ageUpscaling toolbox implements different Python modules to train machine learning models and perform the upscaling of pre-trained models.

{::options parse_block_html="true" /}

<details>
 It allows to generate global forest age map. It can be easily adapted to new datasets and new set of models can be plugged-in.
</details>

## gediwavedl: a Python package for processing and upscaling GEDI L1B waveforms

[gediwavedl code](https://git.gfz-potsdam.de/global-land-monitoring/gedi-lidar-waveform)

The gediwavedl toolbox implements different Python modules to download and process GEDI products. It also allows users to acquire satellite imagery from the microsoft planetary for any GEDI shots.

{::options parse_block_html="true" /}






