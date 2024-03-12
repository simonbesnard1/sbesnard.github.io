---
layout: single
title: "Data"
permalink: /data/
author_profile: true
---

{% include base_path %}

The various datasets I contributed to build up are listed below.

## \[2024\] The Global Age Mapping Integration (GAMI) v1.0 dataset
The GAMv1.0 provides global forest age distributions for 2020 and 2010 at a detailed 100-meter pixel resolution. GAMI employs XGBoost to estimate forest age estimates. This underlying dataset of the GAMI product is a compilation of over 40,000 forest inventory plots, biomass and height measurements, remote sensing observations, and climate data. A key aspect of GAMI's methodology is its integration of Landsat-based disturbance history. This provides a better estimate of the time since the last stand-replacement event for the last 20 years. The data can be explored [here](https://besnardsim.users.earthengine.app/view/globalforestage).

## \[2022\] The FluxnetEO dataset
This dataset provides quality filter, and gap-fill Earth observation data from the MODIS instruments and the Landsat satellites at Fluxnet site level. The methods consistently process surface reflectance in individual spectral bands, derived vegetation indices, and land surface temperature. We offer the community living data sets of pre-processed Earth observation data, where version 2.0 features the MCD43A4/A2 and MxD11A1 MODIS products and Landsat Collection 2 Tier 1 and Tier 2 products in a radius of 2 km around 338 flux sites. The data sets we provide can widely facilitate the integration of activities in the eddy-covariance, remote sensing, and modelling fields. The datasets are openly available [here](https://meta.icos-cp.eu/collections/zuQuNbNKrRPDD2_i-KiPXV0-) for Landsat and [here](https://meta.icos-cp.eu/collections/mdtEHjyujUDsC9vgMv5eeH8B) for MODIS. More details on the FluxnetEO data can be found in the associated [paper](https://doi.org/10.5194/bg-19-2805-2022).

## \[2021\] The MPI-BGC forest age dataset
![MPI-BGC forest age]({{ site.url }}{{ site.baseurl }}/images/Fig6_MLP.png){: .align-left width="50%"}
Here, we created a new global distribution of forest age as of around 2010. This was achieved using a machine learning approach, which we trained with data from over 40,000 forest inventory plots, including information on biomass and climate. The forest age datasets are openly available [here](https://doi.org/10.17871/ForestAgeBGI.2021) and more details on the approach can be found in the associated [paper](https://doi.org/10.5194/essd-13-4881-2021).



