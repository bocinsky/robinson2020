
<!-- README.md is generated from README.Rmd. Please edit that file -->

# robinson2020

[![Travis build
status](https://travis-ci.org/people3k/robinson2020.svg?branch=master)](https://travis-ci.org/people3k/robinson2020)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/people3k/robinson2020/master?urlpath=rstudio)

This repository contains the data and code for our paper:

> Robinson, Erick
> [![](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/0000-0002-0789-3724),
> R. Kyle Bocinsky
> [![](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/0000-0003-1862-3428),
> Jacob Freeman
> [![](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/0000-0001-7402-8450),
> Darcy Bird
> [![](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/0000-0003-3466-6284),
> Robert L.
> Kelly[![](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/0000-0001-9737-0152),
> (2020). *Dendrochronological dates confirm a Late Prehistoric
> population decline in the American Southwest derived from radiocarbon
> dates*. Under review.

<!-- Our pre-print is online here: -->

<!-- > Authors, (YYYY). _Dendrochronological dates confirm a Late Prehistoric population decline in the American Southwest derived from radiocarbon dates_. Name of journal/book, Accessed 05 Feb 2020. Online at <https://doi.org/xxx/xxx> -->

### How to cite

Please cite this compendium as:

> Bocinsky, R. Kyle and Erick Robinson, (2020). *Compendium of R code
> and data for Dendrochronological dates confirm a Late Prehistoric
> population decline in the American Southwest derived from radiocarbon
> dates*. Accessed 05 Feb 2020.

## Contents

The **analysis** directory contains:

  - [:file\_folder: paper](/analysis/paper): R Markdown source document
    for the manuscript. Includes code to reproduce the figures and
    tables generated by the analysis. It also has a rendered version,
    `paper.html`, suitable for reading (the code is replaced by figures
    and tables in this file).
  - [:file\_folder: data](/analysis/data): Data used in the analysis.  
  - [:file\_folder: figures](/analysis/figures): Plots and other
    illustrations

## How to run in your browser or download and run locally

The simplest way to explore the text, code and data is to click on
[binder](https://mybinder.org/v2/gh/people3k/robinson2020/master?urlpath=rstudio)
to open an instance of RStudio in your browser, which will have the
compendium files ready to work with. Binder uses
(rocker-project.org)\[rocker-project.org Docker\] images to ensure a
consistent and reproducible computational environment. These Docker
images can also be used locally.

You can download the compendium as a zip from from this URL:
[master.zip](/archive/master.zip). After unzipping, open the `Proj` file
in RStudio, and run `devtools::install()` to ensure you have the
packages this analysis depends on (also listed in the
[DESCRIPTION](/DESCRIPTION) file). Then open `paper.Rmd` and knit to
produce the `paper.docx`.

Or, simply install straight from Github:

``` r
# install.packages("devtools")
devtools::install_github("people3k/robinson2020")
```

### Licenses

**Text and figures :**
[CC-BY-4.0](http://creativecommons.org/licenses/by/4.0/)

**Code :** [GNU GPLv3](LICENSE.md)

**Data :** [CC-0](http://creativecommons.org/publicdomain/zero/1.0/)
attribution requested in reuse

### Contributions

We welcome contributions from everyone. Before you get started, please
see our [contributor guidelines](CONTRIBUTING.md). Please note that this
project is released with a [Contributor Code of Conduct](CONDUCT.md). By
participating in this project you agree to abide by its terms.

### Acknowledgements

This compendium was created using the [`rrtools` package by Ben
Marwick](https://github.com/benmarwick/rrtools), which is ✨ pure magic ✨
for doing reproducible research.
