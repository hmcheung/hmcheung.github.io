---
layout: archive
title: "Research interest"
permalink: /research/
author_profile: true
---

My research mainly focuses on the impacts and the track forecast of tropical cyclones (TCs) over East Asia.
- [Impacts of tropical cyclones](#impacts-of-tropical-cyclones)
- [Extratropical transition](#extratropical-transition)
- [Machine learning models for tropical cyclone track forecast](#machine-learning-models-for-tropical-cyclone-track-forecast)

<hr style="border:2px solid gray">

## Impacts of tropical cyclones

<ins>Hydrological impact</ins>
<br>
In addition to the East Asian Summer Monsoon, TCs are another major contributor to summer rainfall over East Asia, especially the coastal region. The variability of both TC-induced rainfall and monsoonal rainfall strongly modulates the hydrological cycle and related climate risk in the region. This study analyzes the contribution of TCs to the variability of summertime rainfall in the years of strong versus weak Changma/Baiu (the monsoon season in Korea/Japan). The possible large-scale driver of TC- and non-TC-induced rainfall variability is also examined.

![Differences in TC and non-TC rainfall between strong and weak Changma/Baiu years](/assets/tc_rainfall.jpg)
<br>

<ins>Air pollution</ins>
<br>Numerous studies confirm that a TC near Luzon Strait or Taiwan can create favorable conditions for regional air pollutant episodes (light northerly for pollutant transport, subsidence unfavorable for pollutant dispersion, and increased insolation for enhanced photochemical reaction). These TC-induced episodes can cause higher pollutant concentrations than the others. Our study verifies the impact of TCs on local air quality in summer on a climate scale by investigating the influence of the change in the prevailing TC track over the western North Pacific.

![How typhoon induce air pollution episode](/assets/tc_aq.jpg)

<br>Related article:
- Zeng, S., Chu, J. E., Cheung, H. M., Baek, K., Kim, H. K., & Son, J. H. (2025). <a href="https://www.sciencedirect.com/science/article/pii/S1352231025004728?via%3Dihub" target="_blank">Seasonal Variations in PM2.5 levels in Hong Kong Induced by Eastern and Western Tropical Cyclones</a>. _Atmospheric Environment_. (In press)
- Cheung, H. M., Ho, C. H., Jhun, J. G., Park, D. S. R., & Yang, S. (2018). <a href="https://doi.org/10.1007/s00382-017-4014-1" target="_blank">Tropical cyclone signals on rainfall distribution during strong vs. weak Changma/Baiu years</a>. _Climate Dynamics_, 51, 2311-2320.
- Lam, Y. F., Cheung, H. M., & Ying, C. C. (2018). <a href="https://doi.org/10.1016/j.scitotenv.2017.08.100" target="_blank">Impact of tropical cyclone track change on regional air quality</a>. _Science of the Total Environment_, 610, 1347-1355.

<hr style="border:2px solid gray">

## Extratropical transition

![An example of tropical cyclone and extratropical cyclone](/assets/tc_etc.png)

When TCs move into the mid‑latitudes, they often transform from compact, warm‑core systems into expansive, cold‑core extratropical cyclones that affect much larger areas and populations. In our latest study, we analyzed 445 western North Pacific TCs and identified three objectively defined ET pathways—pinpointing which transitions are most common and which drive the highest post‑transition destructiveness.

In a separate line of work, we used a state‑of‑the‑art Earth system model to assess how elevated atmospheric CO₂ concentrations will reshape global ET activity and the destructiveness of transitioned storms under future‑climate scenarios. Also read this <a href="https://communities.springernature.com/posts/greenhouse-warming-can-lead-to-greater-destructiveness-in-the-mid-latitudes-by-tropical-cyclones" target="_blank">blog post</a>

<br>Related article:
- Cheung, H. M., & Chu, J. E. (2023). <a href="https://www.nature.com/articles/s41612-023-00470-8" target="_blank">Global increase in destructive potential of extratropical transition events in response to greenhouse warming</a>. _npj Climate and Atmospheric Science_, 6(1), 137.
- Cheung, H. M., Ho, C. H., & Chu, J. E. (2025). <a href="https://www.sciencedirect.com/science/article/pii/S2589004225010752" target="_blank">Extratropical transition pathways of tropical cyclones and their role in storm intensity and destructiveness</a>. _iScience_, 28(7), 112814.

<hr style="border:2px solid gray">

## Machine learning models for tropical cyclone track forecast

Physical models have long been the tool for making weather forecasts. Owing to the advancement of computer resources and the availability of tremendous amount of data, machine learning algorithms for weather forecast has gained popularity in recent years. I developed two machine learning models for improving TC track forecast in the medium range (forecast lead time >5 days).

The first model (track-pattern-based model) applies the fuzzy _c_-means clustering method on historical TC tracks similar to an operational 5-day forecast track; makes predictions based on each track pattern; and combines the forecast for each track pattern to form the final forecast. The second model uses different classes of artificial neural networks in concert to correct the TC track predicted by a global weather forecast model (GEFS). The neural network model is improved by including a shortcut connection, feature selection, and hyperparameter tuning. The performance of the deep learning model is evaluated using accuracy, association, and skill.

![Schematic of the track-pattern-based model and deep learning model](/assets/ml_tc.png)

<br>Related article:
- Cheung, H. M., Ho, C. H., Chang, M., Kim, D., Kim, J., & Choi, W. (2021). <a href="https://doi.org/10.1175/WAF-D-20-0102.1" target="_blank">Development of a track-pattern-based medium-range tropical cyclone forecasting system for the western North Pacific</a>. _Weather and Forecasting_, 36(4), 1505-1518.
- Cheung, H. M., Ho, C. H., & Chang, M. (2022). <a href="https://journals.ametsoc.org/view/journals/aies/1/4/AIES-D-21-0003.1.xml" target="_blank">Hybrid neural network models for postprocessing medium-range forecasts of tropical cyclone tracks over the western North Pacific</a>. _Artificial Intelligence for the Earth Systems_, 1(4), e210003.
