# Synthetic Control Methods (SCM) workshop

Here you can find all resources for the IAU workshop on an introduction to synthetic control methods and running a synthetic control analysis in R. This workshop aims to teach the basic principles of the original synthetic control method (Abadie and Gardeazabal  2003; Abadie et al. 2010) and how to run a synthetic control analysis to estimate the impact of an intervention on one or more treated units e.g. a GP practice. In this workshop we also run some introductory data checks and produce descriptive statistics to understand the structure of the fake dataset provided.

Link to [slides](https://thf-evaluative-analytics.github.io/webinar-SCM-workshop/SCM-workshop_R_slides.html#2)

## Workshop instructions

To code along in the workshop you need to download this repo. You can do this either by cloning it or downloading a zip folder by clicking the green code button. You also need to have the following packages installed and recently updated (in the last year). 

* [**here**](https://cran.r-project.org/web/packages/here/index.html)
* [**tidyverse**](https://www.tidyverse.org/)
* [**dplyr**](https://cran.r-project.org/web/packages/dplyr/index.html)
* [**tidyr**](https://cran.r-project.org/web/packages/tidyr.html)
* [**Synth**](https://cran.r-project.org/web/packages/Synth.html)
* [**panelView**](https://cran.r-project.org/web/packages/panelView/index.html)
* [**skimr**](https://cran.r-project.org/web/packages/skimr/index.html) 
* [**tableone**](https://cran.r-project.org/web/packages/tableone/index.html)


### Getting started

The 'workshop' folder contains:

1. SCM-workshop_for_participants.Rmd
* Instructions and exercises for participants.
2. SCM-workshop_for_participants_with_answers.Rmd
* Same as 2 but with possible solutions to the exercises. 


## Data source

This project does not use any real data. We created a fake dataset intended to replicate a GP practice panel data set where 40 GP practices from a CCG called "EA1" received an intervention aimed at reducing hospital utilisation, and 100 GP practices did not receive an intervention.

## Authors

This workshop was created by 

* Geraldine Clarke [Github](www.github.com/geraldineclarke) / [Twitter](www.twitter.com/geraldineCTHF)
* Emma Vestesson  [Github](www.github.com/emma) / [Twitter](www.twitter.com/gummifot)

## References

Abadie, A., and Gardeazabal, J. (2003), “The economic costs of conflict: A case study of the Basque country,” American Economic Review, 93, 113–132. https://doi.org/10.1257/000282803321455188.

Abadie, A., Diamond, A., and Hainmueller, J. (2010), “Synthetic Control Methods for Comparative Case Studies: Estimating the Effect of California’s Tobacco Control Program,” Journal of the American Statistical Association, 105, 493–505. https://doi.org/10.1198/jasa.2009.ap08746.
