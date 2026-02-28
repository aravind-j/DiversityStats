
<!-- 
<img src="https://raw.githubusercontent.com/aravind-j/DiversityStats/master/inst/extdata/DiversityStats.png" alt="" width="20%" />
-->

## `DiversityStats`: Diversity Indices with Statistical Inference

<img src="https://raw.githubusercontent.com/aravind-j/DiversityStats/master/inst/extdata/DiversityStats.png" align="right" alt="logo" width="173" height = "200" style = "border: none; float: right;">

###### Version : [0.0.0.9000](https://aravind-j.github.io/DiversityStats/); License: [GPL-2\|GPL-3](https://www.r-project.org/Licenses/)

##### Aravind, J. and Suman Roy

Division of Germplasm Conservation, ICAR-National Bureau of Plant
Genetic Resources, New Delhi.

------------------------------------------------------------------------

[![minimal R
version](https://img.shields.io/badge/R%3E%3D-3.5.0-6666ff.svg?logo=R)](https://cran.r-project.org/)
[![License: GPL
v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

<!-- [![CRAN_Status_Badge](https://www.r-pkg.org/badges/version-last-release/DiversityStats)](https://cran.r-project.org/package=DiversityStats)
[![Dependencies](https://tinyverse.netlify.app/status/DiversityStats)](https://cran.r-project.org/package=DiversityStats) -->
<!-- [![rstudio mirror downloads](https://cranlogs.r-pkg.org/badges/grand-total/DiversityStats?color=green)](https://CRAN.R-project.org/package=DiversityStats) -->
<!-- 
[![develVersion](https://img.shields.io/badge/devel%20version-0.0.0.9000-orange.svg)](https://github.com/aravind-j/DiversityStats)
-->

[![Github Code
Size](https://img.shields.io/github/languages/code-size/aravind-j/DiversityStats.svg)](https://github.com/aravind-j/DiversityStats)

<!-- [![R-CMD-check](https://github.com/aravind-j/DiversityStats/workflows/R-CMD-check/badge.svg)](https://github.com/aravind-j/DiversityStats/actions) -->

[![Project Status:
WIP](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)
[![lifecycle](https://lifecycle.r-lib.org/articles/figures/lifecycle-maturing.svg)](https://lifecycle.r-lib.org/articles/stages.html#maturing)
[![Last-changedate](https://img.shields.io/badge/last%20change-2026--02--28-yellowgreen.svg)](https://github.com/aravind-j/DiversityStats/)
<!-- [![Zenodo DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.zenodo.14889174.svg)](https://doi.org/10.5281/zenodo.14889174) -->
[![Website -
pkgdown](https://img.shields.io/website-up-down-green-red/https/aravind-j.github.io/DiversityStats.svg)](https://aravind-j.github.io/DiversityStats/)
<!-- [![.](https://pro-pulsar-193905.appspot.com/G-xxxxxxxx/welcome-page)](https://github.com/aravind-j/google-analytics-beacon) -->
<!-- [![GoatCounter](https://DiversityStats-gh.goatcounter.com/count?p=/test)](https://DiversityStats.goatcounter.com/)  -->
<!-- [![packageversion](https://img.shields.io/badge/Package%20version-0.2.3.3-orange.svg)](https://github.com/aravind-j/DiversityStats) -->
<!-- [![GitHub Download Count](https://github-basic-badges.herokuapp.com/downloads/aravind-j/DiversityStats/total.svg)] -->
<!-- [![Rdoc](http://www.rdocumentation.org/badges/version/DiversityStats)](http://www.rdocumentation.org/packages/DiversityStats) -->

------------------------------------------------------------------------

## Description

<!-- Provides a comprehensive framework for analyzing diversity from frequency/abundance count data. Implements a wide range of classical and entropy-based diversity indices, including Berger-Parker, Simpson (and related variants), Shannon, Brillouin, McIntosh, Margalef, Menhinick and Smith-Wilson. Supports permutation-based hypothesis tests for comparing groups with respect to diversity (global and pairwise comparisons), as well as confidence interval estimation using multiple bootstrap methods. Includes functionality for generating diversity profiles based on parametric families such as Hill numbers, Rényi entropy, and Tsallis entropy. The methods are applicable to ecological community data (species abundance counts) and genetic or phenotypic class frequency data. -->

Provides a comprehensive framework for analyzing diversity
fromfrequency/abundance count data. Implements a wide range of classical
andentropy-based diversity indices, including Berger-Parker, Simpson
(andrelated variants), Shannon, Brillouin, McIntosh, Margalef, Menhinick
andSmith-Wilson. Supports permutation-based hypothesis tests for
comparinggroups with respect to diversity (global and pairwise
comparisons), as wellas confidence interval estimation using multiple
bootstrap methods.Includes functionality for generating diversity
profiles based onparametric families such as Hill numbers, Rényi
entropy, and Tsallisentropy. The methods are applicable to ecological
community data (speciesabundance counts) and genetic or phenotypic class
frequency data.

## Installation

<!-- 
The package can be installed from CRAN as follows: 
&#10;
-->

The development version can be installed from github as follows:

``` r
# Install development version from Github
devtools::install_github("aravind-j/DiversityStats")
```

<!-- ## Detailed tutorial
For a detailed tutorial (vignette) on how to used this package type:
&#10;
``` r
browseVignettes(package = 'DiversityStats')
```
The vignette for the latest version is also available [online](https://aravind-j.github.io/DiversityStats/articles.html).-->

## What’s new

To know whats new in this version type:

``` r
news(package='DiversityStats')
```

## Links

<!--[CRAN page](https://cran.r-project.org/package=DiversityStats) -->

[Github page](https://github.com/aravind-j/DiversityStats)

[Documentation website](https://aravind-j.github.io/DiversityStats/)

<!--[Zenodo DOI](https://doi.org/10.5281/zenodo.14889174) -->
<!--
## CRAN checks
&#10;
&#10;
&#10; [![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://cran.r-project.org/web/checks/check_results_DiversityStats.html) 
&#10;
+-----------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Flavour                           | CRAN check                                                                                                                                                                                                         |
+===================================+====================================================================================================================================================================================================================+
| r-devel-linux-x86_64-debian-clang | [![CRAN check -                                                                                                                                                                                                    |
|                                   | r-devel-linux-x86_64-debian-clang](https://badges.cranchecks.info/flavor/r-devel-linux-x86_64-debian-clang/DiversityStats.svg)](https://cran.r-project.org/web/checks/check_results_j.aravind_at_icar.org.in.html) |
+-----------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| r-devel-linux-x86_64-debian-gcc   | [![CRAN check -                                                                                                                                                                                                    |
|                                   | r-devel-linux-x86_64-debian-gcc](https://badges.cranchecks.info/flavor/r-devel-linux-x86_64-debian-gcc/DiversityStats.svg)](https://cran.r-project.org/web/checks/check_results_j.aravind_at_icar.org.in.html)     |
+-----------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| r-devel-linux-x86_64-fedora-clang | [![CRAN check -                                                                                                                                                                                                    |
|                                   | r-devel-linux-x86_64-fedora-clang](https://badges.cranchecks.info/flavor/r-devel-linux-x86_64-fedora-clang/DiversityStats.svg)](https://cran.r-project.org/web/checks/check_results_j.aravind_at_icar.org.in.html) |
+-----------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| r-devel-linux-x86_64-fedora-gcc   | [![CRAN check -                                                                                                                                                                                                    |
|                                   | r-devel-linux-x86_64-fedora-gcc](https://badges.cranchecks.info/flavor/r-devel-linux-x86_64-fedora-gcc/DiversityStats.svg)](https://cran.r-project.org/web/checks/check_results_j.aravind_at_icar.org.in.html)     |
+-----------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| r-patched-linux-x86_64            | [![CRAN check -                                                                                                                                                                                                    |
|                                   | r-patched-linux-x86_64](https://badges.cranchecks.info/flavor/r-patched-linux-x86_64/DiversityStats.svg)](https://cran.r-project.org/web/checks/check_results_j.aravind_at_icar.org.in.html)                       |
+-----------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| r-release-linux-x86_64            | [![CRAN check -                                                                                                                                                                                                    |
|                                   | r-release-linux-x86_64](https://badges.cranchecks.info/flavor/r-release-linux-x86_64/DiversityStats.svg)](https://cran.r-project.org/web/checks/check_results_j.aravind_at_icar.org.in.html)                       |
+-----------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
&#10;
 [![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://cran.r-project.org/web/checks/check_results_DiversityStats.html) 
&#10;
+--------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Flavour                  | CRAN check                                                                                                                                                                                       |
+==========================+==================================================================================================================================================================================================+
| r-devel-windows-x86_64   | [![CRAN check -                                                                                                                                                                                  |
|                          | r-devel-windows-x86_64](https://badges.cranchecks.info/flavor/r-devel-windows-x86_64/DiversityStats.svg)](https://cran.r-project.org/web/checks/check_results_j.aravind_at_icar.org.in.html)     |
+--------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| r-release-windows-x86_64 | [![CRAN check -                                                                                                                                                                                  |
|                          | r-release-windows-x86_64](https://badges.cranchecks.info/flavor/r-release-windows-x86_64/DiversityStats.svg)](https://cran.r-project.org/web/checks/check_results_j.aravind_at_icar.org.in.html) |
+--------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| r-oldrel-windows-x86_64  | [![CRAN check -                                                                                                                                                                                  |
|                          | r-oldrel-windows-x86_64](https://badges.cranchecks.info/flavor/r-oldrel-windows-x86_64/DiversityStats.svg)](https://cran.r-project.org/web/checks/check_results_j.aravind_at_icar.org.in.html)   |
+--------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
&#10;
 [![MacOS](https://img.shields.io/badge/mac%20os-000000?style=for-the-badge&logo=apple&logoColor=white)](https://cran.r-project.org/web/checks/check_results_DiversityStats.html) 
&#10;
+------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Flavour                | CRAN check                                                                                                                                                                                   |
+========================+==============================================================================================================================================================================================+
| r-release-macos-x86_64 | [![CRAN check -                                                                                                                                                                              |
|                        | r-release-macos-x86_64](https://badges.cranchecks.info/flavor/r-release-macos-x86_64/DiversityStats.svg)](https://cran.r-project.org/web/checks/check_results_j.aravind_at_icar.org.in.html) |
+------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| r-oldrel-macos-x86_64  | [![CRAN check -                                                                                                                                                                              |
|                        | r-oldrel-macos-x86_64](https://badges.cranchecks.info/flavor/r-oldrel-macos-x86_64/DiversityStats.svg)](https://cran.r-project.org/web/checks/check_results_j.aravind_at_icar.org.in.html)   |
+------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
-->

## Citing `DiversityStats`

To cite the methods in the package use:

``` r
citation("DiversityStats")
```

    To cite package 'DiversityStats' in publications use:

      Aravind J, Roy S (2026). _DiversityStats: Diversity Indices with
      Statistical Inference_. R package version 0.0.0.9000,
      <https://github.com/aravind-j/DiversityStats>.

    A BibTeX entry for LaTeX users is

      @Manual{,
        title = {DiversityStats: Diversity Indices with Statistical Inference},
        author = {J. Aravind and Suman Roy},
        year = {2026},
        note = {R package version 0.0.0.9000},
        url = {https://github.com/aravind-j/DiversityStats},
      }
