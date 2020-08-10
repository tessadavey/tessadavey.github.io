---
title: "Order-disorder partitioning models"
excerpt: "Order-disorder partitioning models<br/><img src='AlNi_Davey2020.png'>"
collection: research
---

One tool in the CALPHAD arsenal is the four substitutional sublattice order-disorder model, which allows the user to separately specify the energy of ordered phases described with four sublattices and the corresponding disordered solution phase. In the usual four sublattice compound energy formalism approach, it can be challenging to ensure consistency with the disordered phase and the four sublattice model when conditions for disordering are met. The parameterisation for this model is outlined for fcc system by Kusoffsky et al. (binary and ternary) [1] and for bcc systems by Abe et al. (binary) [2] and Lindahl et al. (ternary) [3].

This model can be challenging to understand exactly on a very detailed level. In the general implementation of this method, experimental information describing both the disordered and ordered phases is not available at all temperature. All the parameters are therefore optimised in order to best fit the available data at all points. However, when directly assigning data to both the ordered and disordered phases, for example with first-principles calculations as in [[4]](http://tessadavey.com/research/first_principles_phase_diagrams), this means that a precise understanding of how the parameters in the model are related. A step by step guide to implementing the model is given below. I hope it helps!

*	Implementing the model when only ordered or disordered phase is well known (coming soon). 
*	Implementing the model when both the ordered and disordered phases are well known. This part was included as a supplementary document in [[4]](http://tessadavey.com/research/first_principles_phase_diagrams). 



1. [Kusoffsky A, Dupin N, Sundman B. On the compound energy formalism applied to fcc ordering. Calphad. 2001;25(4):549–65.](https://doi.org/10.1016/S0364-5916(02)00007-X)
2. [Abe T, Shimono M. A description of the effect of short-range ordering in BCC phases with four sublattices. Calphad. 2014;45:40–8.](https://doi.org/10.1016/j.calphad.2013.11.006)
3. [Lindahl BB, Burton BP, Selleby M. Ordering in ternary BCC alloys applied to the Al-Fe-Mn system. Calphad. 2015;51:211–9.](https://doi.org/10.1016/j.calphad.2015.09.008)
4. [Davey T, Tran N-D, Saengdeejing A, Chen Y. First-principles-only CALPHAD phase diagram of the solid aluminium-nickel (Al-Ni) system. Calphad. 2020](http://tessadavey.com/research/first_principles_phase_diagrams)