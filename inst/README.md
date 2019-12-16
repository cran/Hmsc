# Hmsc

## Description

Hierarchical Modelling of Species Communities (**Hmsc**) is a flexible
framework for Joint Species Distribution Modelling (JSDMs). The
framework can be used to relate species occurrences or abundances to
environmental covariates, species traits and phylogenetic
relationships. JSDMs are a special case of species distribution models
(SDMs) that take into account the multivariate nature of communities
which allows us to estimate community level responses as well capture
biotic interactions and the influence of missing covariates in
residual species associations.

The **Hmsc** package contains functions to fit JSDMs, analyze the
output and to generate predictions with these JSDMs. The obligatory
data for a HMSC analysis includes a matrix of species occurrences or
abundances and a matrix of environmental covariates. Optionally, the
user can include information species traits, phylogenetic
relationships and information on the spatiotemporal context of the
sampling design to account for dependencies among the sampling units.

## Getting started

To get started with the package, we recommend to start with reading
the package documentation which can be found by typing
`help('Hmsc-package')`, following the vignettes and reading the help
pages for the `Hmsc`, `HmscRandomLevel` and `sampleMcmc`
functions. The vignettes are available in the 'vignette' folder, or
can be accessed from within **R** by typing e.g. `vignette(topic =
"vignette_1_univariate", package = "Hmsc")`. To see a list of
vignettes, type `vignette(package = "Hmsc")`.

## Documentation

A good place to start for those interested in using the **Hmsc**
package are the following papers:

Ovaskainen, O., Tikhonov, G., Norberg, A., Blanchet, F. G., Duan, L.,
Dunson, D., Roslin, T. and Abrego, N. 2017. How to make more out of
community data? A conceptual framework and its implementation as
models and software. _Ecology Letters_ **20,** 561-576
[https://doi.org/10.1111/ele.12757](https://doi.org/10.1111/ele.12757)

During the development of **Hmsc** several papers have been published
describing the different components of the model. To learn more about
these different components and Joint Species Distribution Modelling in
general we recommend to read these articles.

#### For spatial latent factors:

Ovaskainen, O., Roy, D. B., Fox, R., and Anderson,
B. J. 2017. Uncovering hidden spatial structure in species communities
with spatially explicit joint species distribution models.  _Methods
in Ecology and Evolution,_ **7,** 428-436.
[https://doi.org/10.1111/2041-210X.12502](https://doi.org/10.1111/2041-210X.12502)

#### For analysis of time series data:

Ovaskainen, O., Tikhonov, G., Dunson, D., Grøtan, V., Engen, S.,
Sæther, B.-E. and Abrego, N. 2017. How are species interactions
structured in species rich communities? A new method for analysing
time-series data. _Proceedings of the Royal Society B: Biological
Sciences,_ **284,** 20170768.
[https://doi.org/10.1098/rspb.2017.0768](https://doi.org/10.1098/rspb.2017.0768)

#### For covariate dependent species associations:

Tikhonov, G., Abrego, N., Dunson, D. and Ovaskainen, O. 2017. Using
joint species distribution models for evaluating how
species-to-species associations depend on the environmental
context. _Methods in Ecology and Evolution_ **8,** 443-452.
[https://doi.org/10.1111/2041-210X.12723](https://doi.org/10.1111/2041-210X.12723)
