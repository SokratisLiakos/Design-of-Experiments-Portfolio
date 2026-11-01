# Design of Experiments (DoE) Portfolio

A collection of DoE projects and experimental designs completed during my MSc in Applied Mathematics at NTUA. All analyses are conducted in R.

## Projects Included

* **[01. Fractional Factorial Design](./2^(8-4) FFD/)**: A $2^{8-4}$ fractional factorial design utilizing Lenth's method and Daniel plots to identify significant effects and interactions. Insignificant factors were pooled to gain degrees of freedom for ANOVA, alongside standard diagnostic checks.
* **[02. Factorial Design with Center Points](2-3-center-points)**: A $2^3$ factorial design incorporating 5 center points to test for curvature and determine the necessity of Response Surface Methodology (RSM) like a Central Composite Design (CCD). Includes verification of ANOVA assumptions.
* **[03. Unreplicated Factorial Design](./03-unreplicated-design/)**: Applied Lenth's method to identify significant effects in an unreplicated ($n=1$) $2^4$ design. The design was subsequently projected into a replicated ($n=2$) $2^3$ design to enable formal ANOVA testing.

## Tools & Libraries

* **Language:** R
* **Key Packages:** `DoE.base`, `FrF2`, `rsm`, `ggplot2`

## Datasets

The raw datasets are not hosted in this repository. The data analyzed in these projects are sourced from classic experimental design literature and coursework, specifically:
* Douglas C. Montgomery's *Design and Analysis of Experiments*
* C.F. Jeff Wu and Michael S. Hamada's *Experiments: Planning, Analysis, and Optimization*
* NTUA Applied Mathematics lecture notes
