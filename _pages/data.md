---
layout: single
title: "Data"
permalink: /data/
author_profile: true
---

{% include base_path %}

The various dataset I contributed to build up are listed below.

## \[2024\] 2024 The Global Age Mapping Integration (GAMI) v1.0 dataset
The GAMv1.0 provides global forest age distributions for 2020 and 2010 at a detailed 100-meter pixel resolution. GAMI employs XGBoost to estimate forest age estimates. This underlying dataset of the GAMI product is a compilation of over 40,000 forest inventory plots, biomass and height measurements, remote sensing observations, and climate data. A key aspect of GAMI's methodology is its integration of Landsat-based disturbance history. This provides a better estimate of the time since the last stand-replacement event for the last 20 years. The data can be explore [here](https://besnardsim.users.earthengine.app/view/globalforestage).

## \[2021\] 2021 MPI-BGC – Max Planck Institute for Biogeochemistry – forest age datasets
![MPI-BGC forest age]({{ site.url }}{{ site.baseurl }}/images/Fig6_MLP.png){: .align-left width="50%"}
Here, we created a new global distribution of forest age as of around 2010. This was achieved using a machine learning approach, which we trained with data from over 40,000 forest inventory plots, including information on biomass and climate. The forest age datasets are openly available [here](https://doi.org/10.17871/ForestAgeBGI.2021) and more details on the approach can be found in the associated [paper](https://doi.org/10.5194/essd-13-4881-2021)



