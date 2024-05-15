
# Awesome Cardiac Digital Twins [![Awesome](https://awesome.re/badge.svg)](https://github.com/lileitech/Awesome-Cardiac-Digital-Twins)

This is a curated repository of awesome Cardiac Digital Twin resources. Research and industry leverage cardiac digital twins to simulate and predict individualized responses to interventions, aid in diagnosis and treatment planning, optimize therapy strategies, and personalize patient care.

**Welcome to any contribute to make the resources more complehensive for beginner!**

## Contents

- [Awesome Cardiac Digital Twins ](#awesome-cardiac-digital-twins-)
  - [Contents](#contents)
  - [Definition](#definition)
  - [Research Group](#research-group)
  - [Project](#project)
  - [Software](#software)
  - [Tutorial](#tutorial)
  - [Public Dataset](#public-dataset)
  - [Videos](#videos)
  - [Reference](#reference)

## Definition

Cardiac digital twins are personalized virtual representations combining cardiac images, ECG, and other subject-specific information [1].
CDT workflows usually involve two stages, namely anatomical and functional twinnings, as shown in Fig. 1 [2].

<figure>
  <img src="images/fig_cardiac_digital_twins.png" alt="CDTs" style="width:750px;height:250px;">
  <figcaption>Fig. 1 The cardiac digital twin generation workflow.</figcaption>
</figure>

## Research Group

Here, we summarize the representative research teams and organizations in the computational cardiology and electrocardiography. Note that we only list one PI name, but there may be more than one PI in a team/ lab.

| Team/ Lab                                                                    | PI                | Institute                                       |
|-------------------------------------------------------------------------------------------------|-------------------|------------------------------------------------|
| [Computational Cardiovascular Science Team](https://www.cs.ox.ac.uk/ccs/index.html)             | [Prof Blanca Rodriguez](https://scholar.google.com/citations?user=qYidL6sAAAAJ&hl=en)  | University of Oxford, UK                       |
| [Computational Cardiology Lab (CCL)](https://ccl.medunigraz.at/)                                | [Prof Gernot Plank](https://scholar.google.com/citations?user=HAYpTDYAAAAJ&hl=en)      | Medical University of Graz, Austria             |
| [Trayanova Lab](http://www.trayanovalab.org/)                                                    | [Prof Natalia Trayanova](https://scholar.google.com/citations?user=oY3ePQ8AAAAJ&hl=en) | Johns Hopkins University, US                    |
| [Computational Electrocardiology Lab](https://cvrti.utah.edu/the-macleod-laboratory/)            | [Prof Rob MacLeod](https://scholar.google.com/citations?user=seAo310AAAAJ&hl=en)       | University of Utah, US                         |
| [Modelling and Scientific Computing Laboratory (MOX)](https://mox.polimi.it/)                    | [Prof Alfio Quarteroni](https://scholar.google.it/citations?user=U-iDlKcAAAAJ&hl=en)  | Politecnico di Milano, Italy                    |
| [Cardiac Electro-Mechanics Research Group (CEMRG)](https://www.cemrg.co.uk/)                    | [Prof Steven Niederer](https://scholar.google.com/citations?user=rtBzy78AAAAJ&hl=en)   | Imperial College London, UK                    |
| [Computational Biomedicine Lab (CBL)](https://pht180.rit.edu/cblwang/)                           | [Prof Linwei Wang](https://scholar.google.com/citations?user=CG56DzcAAAAJ&hl=en)       | Rochester Institute of Technology, US          |
| [Computational Cardiology](https://team.inria.fr/epione/en/computational-cardiology/)            | [Prof Maxime Sermesant](https://scholar.google.com/citations?user=LTDUiAkAAAAJ&hl=en)  | Inria, France                                   |
| [Computational Cardiac Modeling Group (CaMo)](https://www.ibt.kit.edu/english/camo.php)          | [Prof Axel Loewe](https://scholar.google.de/citations?user=dLThgu0AAAAJ&hl=de)        | Karlsruhe Institute of Technology, Germany      |
| [Cardiac Electrophysiology Group](https://www.auckland.ac.nz/en/abi/our-research/research-groups-themes/cardiac-electrophysiology.html) | [Prof Bruce Smaill](https://scholar.google.co.nz/citations?user=mUlyaLsAAAAJ&hl=en) | University of Auckland, New Zealand     |
| [Cardiac Computation Lab](https://cclab.med.ucla.edu/)                                           | [Prof Zhilin Qu](https://scholar.google.com/citations?user=WD2JcI4AAAAJ&hl=en)         | University of California, US                    |
| [Computational Arrhythmia Research Lab](http://web.stanford.edu/group/narayanlab/cgi-bin/wordpress/) | Sanjiv Narayan | Stanford University, US                         |
| [Living Matter Lab](https://livingmatter.stanford.edu/)                                           | [Prof Ellen Kuhl](https://scholar.google.com/citations?hl=en&user=jjQDKYYAAAAJ&view_op=list_works&sortby=pubdate)        | Stanford University, US                         |
| [UT-Heart](http://ut-heart.com/)                                                                 | [Prof Toshiaki Hisada](https://dblp.org/pid/29/2299.html)   | University of Tokyo, Japan                      |
| [Leeds Systems Physiology Lab](http://physicsoftheheart.com/LCPL.html)                            | [Prof Michael A Colman](https://scholar.google.co.uk/citations?user=l8u7gSsAAAAJ&hl=en), [Prof Al Benson](https://scholar.google.co.uk/citations?user=XtVFdUkAAAAJ&hl=en) | University Of Leeds, UK             |
| [Digital Heart Modeling Lab](https://lileitech.github.io/)                                        | [Dr Lei Li](https://scholar.google.com/citations?user=--CYiuwAAAAJ&hl=en)            | University of Southampton, UK                   |

## Project

- [Living Heart Project](https://www.3ds.com/products-services/simulia/solutions/life-sciences-healthcare/the-living-heart-project/): Dassault Systèmes (Steven M. Levine)
- [John’s Digital Twin](https://www.siemens-healthineers.com/perspectives/patient-twin-johns-heart): Siemens Healthineers
- [EDITH](https://www.edith-csa.eu/edith/): European Virtual Human Twin
- [Virtual Physiological Human (VPH) Projects](https://www.vph-institute.org/): Virtual Physiological Human Institute, Belgium

## Software

- [openCARP](https://opencarp.org/): open-access cardiac electrophysiology simulator.
- [Paper ECG Digitization Tool](http://ecg-digitisation.hh.med.ic.ac.uk:8050/) [3]: allow users to upload scanned ECGs to extract the digital signals (ECG pre-processing might be required).

## Tutorial

- [EP simulator](https://www.ep-simulator.com/): Basic courses of cardiac electrophysiology.
- [openCARP tutorials](https://opencarp.org/documentation/video-tutorials): Basic courses of cardiac electrophysiology.

## Public Dataset

- [EDGAR database](https://www.ecg-imaging.org/edgar-database): public dataset for the application and validation of ECGI techniques.
- [MyoFit46](https://myofit46.com/): paired high-density surface ECGI and cardiac MRI.
- [UK Biobank](https://www.ukbiobank.ac.uk/): paired cine MRI and 12-lead ECG data.

## Videos

- [Digital twin heart – Computer model for an optimized therapy success](https://www.youtube.com/watch?v=skr_cjJJFrc).
- [Your Personal Virtual Heart | Natalia Trayanova | TEDxJHU](https://www.youtube.com/watch?v=wSDMPxGGy3A&t=618s).
- [Heart research, AI and digital twins](https://www.youtube.com/watch?v=jZz9TfvRHs4).
- [Personalized Cardiology Powered by AI and Computational Modeling - Prof Natalia Trayanova (JHU)](https://www.youtube.com/watch?v=kcwMSqtFPOQ&t=2381s)

## Reference

[1]: Corral-Acero, Jorge, et al. "The ‘Digital Twin’to enable the vision of precision cardiology." European heart journal 41.48 (2020): 4556-4564. [link](https://academic.oup.com/eurheartj/article/41/48/4556/5775673)

[2]: Li, Lei, et al. "Towards Enabling Cardiac Digital Twins of Myocardial Infarction Using Deep Computational Models for Inverse Inference." IEEE Transactions on Medical Imaging (2024). [link](https://ieeexplore.ieee.org/abstract/document/10440104)

[3]: Wu, Huiyi, et al. "A fully-automated paper ECG digitisation algorithm using deep learning." Scientific Reports 12.1 (2022): 20963. [link](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9722713/)

