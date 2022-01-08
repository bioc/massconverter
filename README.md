<!-- README.md is generated from README.Rmd. Please edit that file -->

# massconverter <img src="man/figures/massconverter_logo.png" align="right" alt="" width="120" />

[![](https://www.r-pkg.org/badges/version/massconverter?color=green)](https://cran.r-project.org/package=massconverter)
[![](https://img.shields.io/github/languages/code-size/tidymass/massconverter.svg)](https://github.com/tidymass/massconverter)
[![Dependencies](https://tinyverse.netlify.com/badge/massconverter)](https://cran.r-project.org/package=massconverter)
[![](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)

`massconverter` is a part of [tidymass](https://tidymass.github.io/tidymass/).

------

# About

`massconverter` provide the `mass_dataset` class which is specifically developed and designed to organize the rectangular **metabolomics data sets** into a standard structure. `massconverter` package also provide a lot of base processing functions to process and operate the `mass_dataset` class. In additional, the `mass_dataset` class can be processed by all the packages from [`tidymass`](https://tidymass.github.io/tidymass/).

<img src="man/figures/Figure.png" align="middle" alt="" width = "100%"/>

Merging separate data objects is useful for manually-imported data objects, especially for metabolomics data analysis. It's significant to keep unified format before analysis. While the first category of merging functions is useful for direct manipulations of the data for analytical purposes, `massconverter` is a convenience/support tool to help get your data into the right format.

# Installation

You can install `massconverter` from
[Github](https://github.com/tidymass/massconverter).

``` r
if(!require(devtools)){
install.packages("devtools")
}
devtools::install_github("tidymass/massconverter")
```

More installation information can be found [here](https://tidymass.github.io/massconverter/articles/massconverter_install.html).

# Get started

Please see the "Help documents".

# Need help?

If you have any questions about `massconverter`, please don’t hesitate to
email me (<shenxt@stanford.edu>) or reach out me via the social medias below.

<i class="fa fa-weixin"></i>
[shenxt1990](https://www.shenxt.info/files/wechat_QR.jpg)

<i class="fa fa-envelope"></i> <shenxt@stanford.edu>

<i class="fa fa-twitter"></i>
[Twitter](https://twitter.com/JasperShen1990)

<i class="fa fa-map-marker-alt"></i> [M339, Alway Buidling, Cooper Lane,
Palo Alto, CA
94304](https://www.google.com/maps/place/Alway+Building/@37.4322345,-122.1770883,17z/data=!3m1!4b1!4m5!3m4!1s0x808fa4d335c3be37:0x9057931f3b312c29!8m2!3d37.4322345!4d-122.1748996)

# Citation

If you use massconverter in you publication, please cite this publication:

X. Shen, R. Wang, X. Xiong, Y. Yin, Y. Cai, Z. Ma, N. Liu, and Z.-J.
Zhu\* (Corresponding Author), Metabolic Reaction Network-based Recursive
Metabolite Annotation for Untargeted Metabolomics, Nature
Communications, 2019, 10: 1516.  
[Web Link](https://www.nature.com/articles/s41467-019-09550-x).

Thanks very much!
