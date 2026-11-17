---
permalink: /research/
title: "Research"
author_profile: true
---

{% include toc toc_levels="2" %}
{% include base_path %}

<div style="height:140px;"></div>

## Red Supergiants in M31: Investigating Binary Candidates in Cluster and Field Environments

As part of the [CIERA REU Program](https://sites.northwestern.edu/cierareu/2026-student-cohort/) at Northwestern University, I studied red supergiants (RSGs) in the Andromeda Galaxy using data from the Panchromatic Hubble Andromeda Treasury (PHAT) survey and the Andromeda Project cluster catalog through [Zooniverse](https://www.zooniverse.org). Under the mentorship of [Dr. L. Clifton Johnson](https://sites.northwestern.edu/lcjohnson/), I cross-matched thousands of stars with stellar clusters and developing an age-dependent color and magnitude selection to identify red supergiant candidates. I investigated how cluster properties such as age and mass influence RSG populations and identified candidate binary systems through ultraviolet excess. This project combines large astronomical datasets with statistical analysis to better understand the evolution of massive stars and their role in galaxy evolution.

<p>
    <strong>Research Materials:</strong>
    <a href="{{ base_path }}/files/CIERAREUPoster_LeFevre.pdf" target="_blank">View Poster</a>
    &nbsp;&nbsp;|&nbsp;&nbsp;
    <a href="{{ base_path }}/files/CIERA_REU_Research_Summary_Draft.pdf" target="_blank">View Research Notes</a>
</p>

<h4 style="font-size:1.2em; margin-bottom:10px;">Introduction</h4>

Massive stars play an important role in galaxy evolution through radiation, stellar winds, and supernovae. Evolved helium-burning (HeB) stars, particularly red supergiants, provide important constraints on massive-star evolution, mass loss, and Type II supernova progenitors. Binary interactions can further alter the evolution and observable properties of these stars.
Using PHAT photometry and the Andromeda Project cluster catalog, I identified HeB stars and RSGs associated with M31 star clusters. I focused on the RSG population, comparing cluster and field RSGs, examining their relationship with cluster properties, and searching for evidence of binary companions through UV excess emission.

<h4 style="font-size:1.2em; margin-bottom:10px;">Cluster HeB Star Selection</h4>

Identifying evolved HeB stars that are members of star clusters provides constraints on the ages and properties of these post-main-sequence populations. Cluster membership was assigned to PHAT stars located within the apertures of clusters in the Andromeda Project catalog. PHAT photometry was filtered using signal-to-noise requirements in the optical bands while avoiding overly restrictive sharpness and crowding cuts that can reduce completeness in crowded cluster environments.
HeB candidates were selected based on their position in the optical color-magnitude diagram (F475W−F814W vs. F814W) relative to best-fit Padova isochrones. Candidates were required to be brighter than the main-sequence turn-off (MSTO) and separated from the RGB-tip region using age-dependent boundaries designed to balance completeness and contamination. The analysis focused on clusters with ages appropriate for massive-star RSGs, reducing contamination from older RGB populations.

<figure style="margin:0;">
    <img src="{{ base_path }}/images/CIERA_Cluster980CMD.png"
         alt="Optical CMD of AP Cluster 980 showing the HeB selection region (light pink). The luminosity cut (purple) is offset from the MSTO (black), while the color cut (red) is based on the RGB tip. Boundaries are derived from age-matched Padova solar-metallicity isochrones (light purple). Cluster stars are shown in pink."
         style="width:65%; height:auto; border-radius:0; display:block; margin:auto;">
    <figcaption style="font-size:0.75em; color:#666; text-align:center; margin-top:5px;">
        Optical CMD of AP Cluster 980 showing the HeB selection region (light pink). The luminosity cut (purple) is offset from the MSTO (black), while the color cut (red) is based on the RGB tip. Boundaries are derived from age-matched Padova solar-metallicity isochrones (light purple). Cluster stars are shown in pink.
    </figcaption>
</figure>

<h4 style="font-size:1.2em; margin-bottom:10px;">Results</h4>
<h4 style="font-size:1em; margin-bottom:10px;">Cluster RSG Sample</h4>

I identified 424 HeB stars across 237 clusters, including 252 RSGs and 170 BSGs. RSGs and BSGs were separated using their F110W−F160W color, with RSGs defined as having F110W−F160W ≥ 0.78. Some contamination from yellow supergiants is possible in both populations.
RSG-hosting clusters span log(age/yr) = 6.60–8.00, with approximately 58% of the identified RSGs in the oldest age bin (7.75–8.00). I also calculate the RSG production efficiency of the cluster population as a function of cluster mass to investigate how efficiently clusters produce observable RSGs.

<div style="display:grid; grid-template-columns:repeat(2,1fr); gap:10px;">
<figure style="margin:0;">
    <img src="{{ base_path }}/images/CIERA_DereddenedOPTCMD.png" 
         alt="Dereddened optical color-magnitude diagram (CMD) of cluster selected HeB stars. RSGs are indicated in red and BSGs in blue. Pavova isochrones of log(age/yr) = 7.0, 7.5, 8.0 are over plotted for reference."
         style="width:85%; height:auto; border-radius:0; display:block; margin:auto;">
    <figcaption style="font-size:0.75em; color:#666; text-align:center; margin-top:5px;">
        Dereddened optical color-magnitude diagram (CMD) of cluster selected HeB stars. RSGs are indicated in red and BSGs in blue. Pavova isochrones of log(age/yr) = 7.0, 7.5, 8.0 are over plotted for reference.
    </figcaption>
</figure>
<figure style="margin:0;">
    <img src="{{ base_path }}/images/CIERA_IRCMD.png" 
         alt="Infrared CMD of PHAT stars (gray) and CMD-selected HeB stars, with RSGs shown in red and BSGs in blue. The dashed lines show the RSG selection criteria from Dai et al. (2025)1, illustrating the difference between our broader selection and the more restrictive criteria used in their RSG catalog."
         style="width:85%; height:auto; border-radius:0; display:block; margin:auto;">
    <figcaption style="font-size:0.75em; color:#666; text-align:center; margin-top:5px;">
        Infrared CMD of PHAT stars (gray) and CMD-selected HeB stars, with RSGs shown in red and BSGs in blue. The dashed lines show the RSG selection criteria from Dai et al. (2025)1, illustrating the difference between our broader selection and the more restrictive criteria used in their RSG catalog.    
    </figcaption>
</figure>
</div>

<figure style="margin:0;">
    <img src="{{ base_path }}/images/CIERA_CCD.png" 
         alt="Color-color diagram of PHAT stars (gray) and CMD-selected HeB stars, with RSGs shown in red and BSGs in blue. Main-sequence stars, foreground stars, BSGs, and RSGs are labeled to show the separation between the major stellar populations."
         style="width:45%; height:auto; border-radius:0; display:block; margin:auto;">
    <figcaption style="font-size:0.75em; color:#666; text-align:center; margin-top:5px;">
        Color-color diagram of PHAT stars (gray) and CMD-selected HeB stars, with RSGs shown in red and BSGs in blue. Main-sequence stars, foreground stars, BSGs, and RSGs are labeled to show the separation between the major stellar populations.
    </figcaption>
</figure>

<h4 style="font-size:1em; margin-bottom:10px;">PHAT-wide RSG Sample</h4>

To compare the cluster population with RSGs across M31, I developed a PHAT-wide RSG selection using near-infrared color-magnitude criteria, along with an optical–NIR cut to reduce contamination from asymptotic giant branch (AGB) stars. The selection was based in part on the RSG criteria of Dai et al. (2025), while using photometric quality cuts designed to preserve completeness.
This selection identifies 5,188 RSGs across PHAT, including 99 associated with clusters. For comparison, the RSG catalog of Dai et al. (2025) contains 2,612 RSGs, including 81 cluster-associated RSGs. Differences between these samples primarily reflect differences in photometric quality cuts and RSG selection criteria. The PHAT-wide sample provides a larger RSG population for comparing cluster and field environments, particularly at older ages.

<div style="text-align:center;">
    <img src="{{ base_path }}/images/CIERA_RSGagebinsplots.png"
         alt="RSG population properties as a function of cluster age for the CMD-selected cluster RSG sample."
         style="width:65%; height:auto; border-radius:0;">

    <p style="font-size:0.75em; color:#666; text-align:center; margin-top:5px;">
        RSG population properties as a function of cluster age for the CMD-selected cluster RSG sample. The top panel shows the number of RSGs and the bottom panel shows the RSG production efficiency per unit cluster mass. Points show the mean cluster age within each age bin with Poisson uncertainties, and grey error bars show bin width.
    </p>
</div>

<div style="height:40px;"></div>

<div style="text-align:center; margin-top:20px;">
    <img src="{{ base_path }}/images/CIERA_RSGStatsTable.png"
         alt="Number of red supergiants (RSGs) and associated clusters identified in each RSG sample."
         style="width:85%; height:auto; border-radius:0;">

    <p style="font-size:0.75em; color:#666; text-align:center; margin-top:5px;">
        Number of red supergiants (RSGs) and associated clusters identified in each RSG sample, showing the differences between the cluster CMD selection, the PHAT-wide selection, and the Dai et al. (2025) catalog.
    </p>
</div>

<h4 style="font-size:1.2em; margin-bottom:10px;">Binary Candidates</h4>

Ultraviolet excess can reveal hot companions to cool RSGs, which produce relatively little UV emission themselves. I identify candidate binaries using an F336W−F814W vs. F814W−F160W color-color criterion inspired by Dai et al. (2025). An F336W signal-to-noise requirement of >4 was used to ensure reliable UV detections, while F275W was excluded because its shallower depth would bias the sample toward brighter UV sources.
The observed UV excess is consistent with the presence of a main-sequence companion with a mass of approximately 3–5 M⊙ or greater. The candidate binary fraction is 2.18× higher among cluster-associated RSGs than field RSGs (25.3% vs. 11.6%). This difference provides a potential test of whether stellar environment influences the binary properties and evolution of RSGs.

<figure style="margin:0;">
    <img src="{{ base_path }}/images/CIERA_UVExcess.png" 
         alt="Color-color diagram of CMD-selected RSGs showing the UV-excess binary candidates. Single RSGs are shown in red and binary candidates in purple. The PHAT-wide RSG sample is shown in grey for comparison. The dashed line marks the boundary used to identify UV excess and is inspired by the UV excess plots of Dat et al. (2025)."
         style="width:65%; height:auto; border-radius:0; display:block; margin:auto;">
    <figcaption style="font-size:0.75em; color:#666; text-align:center; margin-top:5px;">
        Color-color diagram of CMD-selected RSGs showing the UV-excess binary candidates. Single RSGs are shown in red and binary candidates in purple. The PHAT-wide RSG sample is shown in grey for comparison. The dashed line marks the boundary used to identify UV excess and is inspired by the UV excess plots of Dat et al. (2025).
    </figcaption>
</figure>

<div style="height:40px;"></div>

<figure style="margin:0;">
    <img src="{{ base_path }}/images/CIERA_BinaryTable.png" 
         alt="Binary fractions for the RSG samples, comparing cluster-associated and field RSG populations."
         style="width:85%; height:auto; border-radius:0; display:block; margin:auto;">
    <figcaption style="font-size:0.75em; color:#666; text-align:center; margin-top:5px;">
        Binary fractions for the RSG samples, comparing cluster-associated and field RSG populations.
    </figcaption>
</figure>

<h4 style="font-size:1.2em; margin-bottom:10px;">Ongoing Work</h4>

Future work will focus on comparing the observed RSG populations with single-star and binary stellar evolution models to determine whether the observed trends are consistent with theoretical predictions. I will also investigate how the binary-candidate fraction varies with cluster age to explore whether binary interactions become more or less important at different stages of massive-star evolution. Finally, I will examine completeness trends as a function of age to determine how observational biases and selection effects may influence the observed RSG populations, particularly at older ages. Together, these analyses will help distinguish evolutionary trends from observational effects and provide a more complete picture of RSG and binary evolution.

<h4 style="font-size:1.2em; margin-bottom:10px;">Acknowledgements</h4>

I gratefully acknowledge the support of the CIERA  Research Experiences for Undergraduates (REU) program at Northwestern Univeristy. This material is based upon work supported by the U.S. National Science Foundation under Award No. AST-2446392.  Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the NSF.

<h4 style="font-size:1.2em; margin-bottom:10px;">References</h4>


<div style="font-size:0.75em;">
    <p>Dai, M., Wang, S., Jiang, B., & Li, Y. 2025, ApJ, 988, 60.</p>
    <p>Dalcanton, J. J., Williams, B. F., Lang, D., et al. 2012, ApJS, 200, 18.</p>
    <p>Girardi, L., Williams, B. F., Gilbert, K. M., et al. 2010, ApJ, 724, 1030.</p>
    <p>Johnson, L. C., Seth, A. C., Dalcanton, J. J., et al. 2015, ApJ, 802, 127, doi: 10.1088/0004-637X/802/2/127</p>
    <p>Marigo, P., Girardi, L., Bressan, A., et al. 2008, A&A, 482, 883, doi: 10.1051/0004-6361:20078467</p>
    <p>Neugent, K. F. 2021, ApJ, 908, 87, doi: 10.3847/1538-4357/abd47b</p>
    <p>Williams, B. F., Durbin, M., Lang, D., et al. 2023, ApJS, 268, 48, doi: 10.3847/1538-4365/acea61</p>
</div>

-----

## Classifying Galactic Center Sources Through X-ray Time-Domain Analysis

I am currently investigating X-ray point sources near the Galactic Center using data from the [Chandra X-ray Observatory](https://science.nasa.gov/mission/chandra/) under the guidance of [Dr. Dustin Swarm](https://physics.uiowa.edu/people/dustin-swarm). The Galactic Center contains thousands of X-ray point sources with spectra consistent with cataclysmic variables (CVs), close binary systems in which a white dwarf (WD) accretes material from a companion star. As material falls toward the WD, it heats to extreme temperatures and produces X-ray emission. However, dust absorption makes these sources difficult to study at lower X-ray energies.

Analysis of the combined spectra suggests that Galactic Center CVs have unusually low average WD masses compared to other CV populations. This discrepancy may result from combining spectra across multiple CV subtypes with different accretion geometries and temperatures, rather than accurately representing the underlying WD mass distribution. Understanding the composition of this population is therefore important for improving WD mass estimates and investigating current models of stellar and Galactic evolution. WD masses can be estimated from the temperature of the accreted gas, which is related to the WD's gravitational potential. However, this relationship depends on the accretion geometry and assumes that no energy is lost through other cooling processes, such as those associated with an accretion disk. Iron emission lines provide additional information about plasma conditions and accretion geometry, but they are not always sufficient to conclusively distinguish CV subtypes.

CVs are broadly classified according to the strength of the WD's magnetic field, which determines how material accretes onto the WD. **Polars** have strong magnetic fields that prevent accretion disk formation and channel material directly onto the magnetic poles. Their strong fields also produce cyclotron cooling, providing an additional mechanism for removing energy from the accreted gas. The WD spin is synchronized with the binary orbit, producing variability at the orbital period. **Intermediate polars (IPs)** have moderately strong magnetic fields that partially disrupt the accretion disk, channeling some material onto the magnetic poles. Their WD spin and orbital periods are distinct, potentially producing variability at both periods. **Dwarf novae (DNe)** have weak magnetic fields that allow a full accretion disk to form around the WD, with variability potentially occurring at the orbital period. IPs and DNe can exhibit similar X-ray spectral characteristics, making them difficult to distinguish through spectroscopy alone.

<figure style="margin:0;">
    <img src="{{ base_path }}/files/CV_Types.png" 
         alt="Schematic diagrams of the three main types of cataclysmic variables, arranged by magnetic field strength: dwarf nova (left), intermediate polar (middle), and polar (right.)"
         style="width:95%; height:auto; border-radius:0; display:block; margin:auto;">
    <figcaption style="font-size:0.75em; color:#666; text-align:center; margin-top:5px;">
        Schematic diagrams of the three main types of cataclysmic variables, arranged by magnetic field strength: dwarf nova (left), intermediate polar (middle), and polar (right).
    </figcaption>
</figure>

To address these classification challenges, I am performing time-domain analysis of X-ray light curves for approximately 34 Galactic Center sources. X-ray light curves track changes in source brightness over time, revealing periodic signals associated with physical processes within each binary system. By searching for variability associated with WD spin and orbital periods, I aim to identify signatures of different CV subtypes and better constrain their accretion geometries.

My work involves incorporating periodicity search algorithms into a software pipeline for processing and analyzing Chandra light curves. Current efforts focus on identifying candidate periodic signals, characterizing X-ray variability, and evaluating potential classifications for each source. Ultimately, distinguishing between magnetic and non-magnetic CVs will help refine WD mass estimates, investigate the unusually low masses inferred for the Galactic Center population, and improve our understanding of accreting compact binary systems.

<p>
    <strong>Research Materials:</strong>
    <a href="{{ base_path }}/files/UIowa_Poster.pdf" target="_blank">View Poster</a>
</p>

