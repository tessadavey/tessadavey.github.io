---
title: "Sequential learning via uncertainty quantification"
excerpt: "Sequential learning via uncertainty quantification<br/><img src='AlNi_uq_Davey2020.png'>"
collection: research
---

A methodology has been developed that uses quantified uncertainty to determine a pathway to a well-assessed CALPHAD phase diagram using the least possible experimental data. This methodology may be used to improve understanding of existing phase diagrams, or to explore unknown systems. Starting from a first-principles description, ESPEI [1] is used within Pycalphad [2] to automatically fit appropriate parameters for a thermodynamic description. Then the uncertainty of the description is quantified and propagated to the phase diagram using PDUQ [3]. The parts of the phase diagram with the highest uncertainty are determined and experimental data can be selected in this region. This may be performed iteratively until the uncertainty has been reduced to an acceptable level. It has been shown for the aluminium-nickel system (based on work in [4]) that this can significantly reduce the number of experiments needed to reduce the uncertainty to a chosen level, which has the potential to reduce time and expense in materials investigations.

This collaborative work with Brandon Bocklund and Zi-Kui Liu from Penn. State University has been presented at TMS (2020) and is being prepared for publication.  

1. [Bocklund B, Otis R, Egorov A, Obaied A, Roslyakova I, Liu Z-K. ESPEI for efficient thermodynamic database development, modification, and uncertainty quantification: application to Cu–Mg. MRS Commun. 2019;9:618–27.](https://doi.org/10.1557/mrc.2019.59)
2. [Otis R, Liu Z-K. pycalphad: CALPHAD-based Computational Thermodynamics in Python. J Open Res Softw. 2017;5(1):1.](http://doi.org/10.5334/jors.140)
3. [Paulson NH, Bocklund BJ, Otis RA, Liu Z, Stan M. Quantified Uncertainty in Thermodynamic Modeling for Materials Design. Acta Mater. 2019;174:9–15.](https://doi.org/10.1016/j.actamat.2019.05.017)
4. [Davey T, Tran N-D, Saengdeejing A, Chen Y. First-principles-only CALPHAD phase diagram of the solid aluminium-nickel (Al-Ni) system. Calphad. 2020](http://tessadavey.com/research/first_principles_phase_diagrams)