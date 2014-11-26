decompr-article
===============

Bastiaan Quast and Victor Kümmritz
---------------------

Abstract
----------------
The R package **decompr** implements algorithms for the analysis of Global Value Chains.
Two methods for gross export flow decomposition using Inter-Country Input-Output tables are provided.
The first method is the **Wang-Wei-Zhu** [-@wang2014quantifying] algorithm which splits bilateral gross exports into 16 value added components.
These components can broadly be divided into domestic and foreign value added.
The second method concerns a **source decomposition** algorithm.
This derives the value added origin of a country-industry’s exports by source country and source industry,
by applying the basic Leontief insight to gross trade data.
This article summarises the methodology of the algorithms and describes the format of the input and output data.


Introduction
------------------
Global Value Chains (GVCs) have become a central factor in trade and development policy.
Policy makers from different countries and institutions have placed them at the center of their agenda
and continuously emphasize their growing importance for both international trade and economic development.
However, analysing this phenomenon empirically requires complex matrix manipulations,
since the relevant data is only available in the form of gross flows.
This package enables researchers with little background in matrix algebra and linear programming
to easily derive standard GVC indicators for statistical analysis.

Wang Wei Zhu
-------------------
 * Small derivation
 * R demonstration using WIOD data
 * 
 
Source Decomposition
------------------------
 * Small derivation
 * R demonstration using WIOD data

Input and Output Data
----------------------


Discussion
------------------------


Acknowledgement
--------------------
FNS
Fei Wang


References
----------------------
