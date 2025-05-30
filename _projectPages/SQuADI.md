---
title: Spectroscopic Quasar Anomaly Detection (SQuAD) I
description: Rest frame UV spectra from SDSS DR16
---

# Aim

We present the results of applying anomaly detection algorithms to a
quasar spectroscopic subsample from the SDSS DR16 quasar catalog,
covering the redshift range of 1.88 $\leq$ z $\leq$ 2.47. A principal
component analysis (PCA) was employed for the dimensionality reduction
of the quasar spectra, followed by a hierarchical k-means clustering in
a 20-dimensional PCA eigenvector hyperspace. To prevent broad absorption
line (BAL) quasars from being identified as the primary anomaly group,
we conducted separate analyses on BAL and non-BAL quasars (a.k.a. QSOs),
comparing both classes for a clearer identification of other anomalous
quasar types. We identified 2066 anomalous quasars, categorized into 10
broadly defined groups. The anomalous groups include:
C IV Peakers: quasars with extremely strong and narrow C IV emission
lines; Excess Si IV emitters: quasars where the Si IV line is as strong
as the C IV line; and Si IV deficient anomalies: which exhibit
significantly weaker Si IV emission compared to typical quasars. The
anomalous nature of these quasars is attributed to lower Eddington
ratios for C IV Peakers, supersolar metallicity for Excess
Si IV emitters, and subsolar metallicity for Si IV deficient anomalies.
Additionally, we identified four groups of BAL anomalies: blue BALs,
flat BALs, reddened BALs, and FeLoBALs, distinguished primarily by the
strength of reddening in these sources. Furthermore, among the non-BAL
quasars, we identified three types of reddened anomaly groups classified
as heavily reddened, moderately reddened, and plateau-shaped spectrum
quasars, each exhibiting varying degrees of reddening. We present the
detected anomalies as an accompanying value-added catalog.

<p align="center">
  <a href="https://github.com/ArihantTiwari/SQuAD/blob/main/_projectPages/Papers/aa53330_24.pdf">
    <img src="https://img.shields.io/badge/Download_Paper-PDF-blue?style=for-the-badge" alt="Download Paper">
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://arxiv.org/abs/2411.16858">
    <img src="https://img.shields.io/badge/View_on-ArXiv-orange?style=for-the-badge" alt="arXiv">
  </a>
</p>

# Catalog

 
  | Name                        |  RA  (deg)   |  Dec (deg)  |   Redshift  |  R-band  magnitude |  Cluster ID  |  Group ID  |  Anomaly Type     |
  | :-------------------------- | :----------: | :---------: | :--------:  | :-----------:      | :---------:  |  :-------: | : -------------- :|
  | SDSS J001439.18-045138.9    | 3.6632       | -4.8608     |2.1261       |21.19               |1             | 1          | C iv peaker       |
  | SDSS J102835.79+262923.4    | 157.1491     | 26.4898     |2.0888       |18.50               |2             | 4          | Excess Si iv      |
  | SDSS J002048.12-032444.4    | 5.2005       | -3.4123     |1.9333       |20.24               |2             | 2          | Si iv deficient   |
  | SDSS J091333.72+132541.3    | 138.3905     | 13.4281     |2.1168       |19.21               |2             | 4          | Blue BAL          |
  | SDSS J000228.71+103732.8    | 0.6196       | 10.6257     |1.9522       |20.68               |2             | 2          | Flat BAL          |
  | SDSS J091836.30+523711.0    | 139.6512     | 52.6197     |1.9157       |19.91               |3             | 3          | Red BAL           |
  | SDSS J123015.99+062056.7    | 187.5666     | 6.3491      |1.8512       |20.05               |2             | 3          | FeLoBAL           |
  | SDSS J125831.40+522124.6    | 194.6308     | 52.3568     |1.9237       |19.89               |3             | 3          | Heavy red         |
  | SDSS J133017.54+044646.4    | 202.5731     | 4.7795      |2.2054       |18.79               |3             | 3          | Moderate red      |
  | SDSS J124331.66+520335.1    | 190.8819     | 52.0597     |2.1730       |18.51               |3             | 3          | Plateau-shaped    |
 
<p align="center">
  <a href="https://github.com/ArihantTiwari/SQuAD/blob/main/Catalogs/SQuAD_I_catalog.csv">
    <img src="https://img.shields.io/badge/Download_Full_Catalog-CSV-green?style=for-the-badge" alt="Download Catalog">
  </a>
</p>

# Conclusion {#sec:Conclusion}

Applying hierarchical k-means clustering in a 20-dimensional PCA
eigenvector hyperspace representing quasar spectra. We have presented
five broad categories of quasar anomalies divided into 10 homogeneous
groups:

1.  C iv Peakers: A total of 299 quasars with an extremely strong, yet
    narrow (median $\sim2000$km s$^{-1}$) C iv emission line.

2.  Excess Si iv emitters: Quasars in this group exhibit an excessively
    high Si iv  to C iv  emission line flux ratio, nearly double the
    median value observed for all quasars in @Wu_2022 catalog. A total
    of 227 such quasars were found.

3.  Si iv deficient anomalies: 328 quasars with disproportionately low
    Si iv emission with Si iv to C iv flux ratio being one third of the
    median ratio for all quasars in @Wu_2022 catalog.

4.  BAL anomalies: A total of 871 quasars were identified as anomalies
    with BAL profiles. These were further subdivided into four subgroups
    as follows:

    -   Blue BALs: A total of 103 HiBAL quasars with a strong negatively
        sloped ("blue") continuum which is atypical of a BAL quasar.

    -   Flat BALs: 371 BAL quasars with a relatively flat continuum.
        Among these, 80% are LoBAL quasars

    -   Reddened BALs: A total of 276 BAL quasars with heavily reddened
        continuum, hence, with a strongly positive slope spectra.

    -   FeLoBALs: These are a very rare class of BAL quasars with strong
        Fe absorptions and heavily reddened continua. There are a total
        of 121 such quasars detected.

5.  Reddened anomalies: A total of 341 quasars were identified as
    reddened anomalous quasars, characterized by extreme reddening, as
    evident from their significantly red spectral slope. They were
    further subdivided into three subgroups primarily based on the
    degree of reddening, as follows:

    -   Heavily reddened quasars: A total of 165 quasars were identified
        with steep, positively sloped spectra, attributed to heavy dust
        reddening.

    -   Moderately reddened quasars: Dust reddened quasars with
        relatively flat or slightly convex shaped continuum. A total of
        93 such quasars were found.

    -   Plateu-shaped spectrum quasars: A total of 83 peculiar quasars
        were identified with a plateau-shaped spectrum, characterized by
        a flat continuum followed by a negatively sloped continuum.
        These quasars exhibit a nearly flat continuum between 1250 and
        2000 Å, which then rapidly declines as the wavelength increases
        from 2000 to 3000 Å.

In our analysis, we initially applied the methodology to the entire
dataset without distinguishing BAL quasars from non-BAL quasars. This
approach aimed to demonstrate what one would obtain if all spectra were
analyzed without prior classifications; that is, working with spectral
data as they are obtained by the spectroscopic surveys. However, this
resulted in groups that were not as pure, making interpretation more
challenging. Ultimately, we found that preclassifying BAL quasars
significantly simplified the process and led to much cleaner and more
distinct groupings. This highlights the importance of BAL classification
as a preliminary step when working with large spectroscopic datasets. We
recommend that future studies employing similar techniques first isolate
BAL quasars before applying clustering or statistical analyses to ensure
clearer and more meaningful results.

This work has significantly expanded the number of sources in each
anomalous quasar group. For example, we present a sample of 121 extreme
FeLoBALs with strong, broad Fe ii  absorption, along with an additional
127 FeLoBALs from the red BAL anomalies, where the iron absorption lines
are considerably narrower. We have developed an efficient method for
identifying anomalous quasars and classifying them into distinct
categories. The detected anomalies are presented in a value-added
catalog, available at the SQuAD website[^1]. This approach has been
successfully applied to the rest-frame UV spectra from the SDSS DR16
catalog and is currently being prepared for broader implementation. We
applied the same algorithm to rest-frame optical spectra from SDSS DR16,
covering around 75,000 quasars in the redshift range $0.1\leq z\leq1.1$,
including key emission lines such as O iii, H$\beta$, and optical iron.
This catalog will be crucial, as these emission lines, particularly in
the context of Eigenvector 1, are tightly correlated with the accretion
rate and orientation of quasars [see @shen2014diversity]. The catalog is
currently under preparation.

With upcoming large-scale surveys such as Dark Energy Spectroscopic
Instrument (DESI), 4-metre Multi-Object Spectroscopic Telescope (4MOST),
and William Herschel Telescope (WHT) Enhanced Area Velocity Explorer
(WEAVE), the number of quasar spectra will increase significantly, and
our methodology will aid in identifying anomalous quasars in these vast
datasets. Additionally, our approach can be adapted for photometric
surveys, such as the Legacy Survey of Space and Time (LSST) survey, to
find photometrically anomalous quasars. By extending the sample size of
these anomalous quasars, this study enables the statistical analysis of
these peculiar sources, contributing to a deeper understanding of AGNs
and their diverse characteristics.
