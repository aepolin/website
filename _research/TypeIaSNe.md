---
layout: project
title: Type Ia Supernovae
caption: I am a leading expert in one of the pathways to Type Ia supernovae – the double detonation mechanism. In this scenario a White Dwarf is able to explode below the Chandrasekhar mass limit through the aid of an accreted helium shell. An ignition of this helium can send a shock wave into the center of the WD which, upon convergence, can ignite the core, causing a thermonuclear runaway resulting in a Type Ia-like explosion. 
description: >
  2D hydrodynamic simulation of a double detonation arising from the ignition of a thick helium shell [Polin 2020](https://ui.adsabs.harvard.edu/abs/2020PhDT........22P/abstract).
date: '10-01-2023'
image: 
  path: /assets/research/2D_ddet.jpg
  srcset: 
    1920w: /assets/research/2D_ddet.jpg
    960w:  /assets/research/2D_ddet.jpg
    480w:  /assets/research/2D_ddet.jpg
links:
  - title: Public Models
    url: https://github.com/aepolin/DoubleDetonationModels
  - title: Original Paper
    url: https://ui.adsabs.harvard.edu/abs/2019ApJ...873...84P/abstract
featured: false
sitemap: false
---
Type Ia SNe are among the most common astrophysical transients, yet their progenitors are still unknown. Despite this they are used as cosmological distance measures, or standard candles. Historically the similarities in the light curve shape of SNe Ia led the community to believe that these events must all arise from a single explosion progenitor channel, but with modern observations that concept has been thrown into doubt as these explosions show much more variety than previously understood. It has now been shown that there is no one progenitor that can explain all SNe Ia, but instead the population is likely composed of multiple progenitor channels, complicating our ability to standardize these events. Likely progenitor candidates include a near-Chandrasekhar mass WD explosion that occurs in a binary with either a degenerate or non-degenerate companion, a merger of two WDs, and/or an explosion of a sub-Chandrasekhar WD through the double detonation mechanism. It is an open question exactly what percentage of SNe Ia are created through which progenitor channel. Having multiple sources of Type Ia SNe complicates our ability to measure the Hubble Constant (H<sub>0</sub>) for cosmology. We must understand how to adjust our standardization methods to account for each of these unique progenitor pathways and be able to accurately identify which SNe Ia should be standardized in which manner. The demographics of SNe Ia also has important implications as we try to understand galactic chemical evolution, as Type Ia SNe are the primary source of Fe-group elements, and each progenitor channel predicts different nucleosynthetic feedback into their hosts.

My work on Type Ia supernovae mainly focuses on the double detonation mechanism. In this scenario a White Dwarf is able to explode below the Chandrasekhar mass limit through the aid of an accreted helium shell. An ignition of this helium can send a shock wave into the center of the WD which, upon convergence, can ignite the core, causing a thermonuclear runaway resulting in a Type Ia-like explosion. I modeled these explosions and determined their observational signatures. In doing so I identified a population of SNe Ia that likely arise from this progenitor channel and for the first time developed an empirical method for categorizing SNe Ia based on their differing physical origins.

<center>
<img src="/assets/research/polinplot.jpg" alt="PolinPlot2019" style="width:150"/>
<span style="font-size: small"> <span style="line-height: 0.1em"> My double detonation models (squares) exhibit a relationship between luminosity and velocity (the dashed line). Observed events fall into two categories, those that follow this relationship and those that cluster above it suggesting that SNe Ia arise from more than one progenitor channel.</span></span>
</center>
\
The mass of the accreted helium shell is the dominant factor in whether or not a double detonation can look like a Type Ia SN. For a sufficiently thin helium shell (either accreted from a degenerate companion or transferred during the a very close binary interaction--the D<sup>6</sup> mechanism) a double detonation can lead to a Type Ia SN. A double detonation triggered by a thick helium shell (accreted from a non-degenerate companion such as a He subdwarf) leads to an event with signatures not exhibited by normal Type Ia SNe. My thin shell explosion models predict a relationship between peak magnitude and velocity that we leveraged to discover a population of observed SNe Ia consistent with this progenitor scenario (see the above figure). Since we first published, it has been shown that the SNe in this population are redder, more polarized, and show stronger [Ca II] emission features than typical SNe Ia. This evidence strongly suggests that SNe Ia arise from more than one progenitor channel, and for the first time provides an empirical method for classifying events based on their physical origin. These models are public and can be found [here](https://github.com/aepolin/DoubleDetonationModels). Using them with the phase I ZTF SNe Ia, current rate estimates for double detonations place them as consistent with roughly 60% of SNe Ia.  
