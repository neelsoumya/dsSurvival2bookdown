
## Introduction

[![License](https://img.shields.io/badge/license-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0.html)

This is a bookdown with executable code demonstrating how to use the dsSurvival package to create privacy preserving survival models in DataSHIELD. dsSurvival builds privacy preserving survival models.

DataSHIELD is a platform for federated analysis of private data. This package can be used to build survival models, Cox proportional hazards models or Cox regression models.

The complete bookdown is available here:

https://neelsoumya.github.io/dsSurvival2bookdown/

DataSHIELD has a client-server architecture and this package has a client side and server side component.

  * The server side package is called dsSurvival:
      
      https://github.com/neelsoumya/dsSurvival

  * The client side package is called dsSurvivalClient:
      
      https://github.com/neelsoumya/dsSurvivalClient




If you use the code, please cite the following manuscript:

Banerjee S, Sofack G, Papakonstantinou T, Avraam D, Burton P, et al. (2022), dsSurvival: Privacy preserving survival models for federated individual patient meta-analysis in DataSHIELD, bioRxiv: 2022.01.04.471418.

https://www.biorxiv.org/content/10.1101/2022.01.04.471418v2

https://doi.org/10.1101/2022.01.04.471418

https://bmcresnotes.biomedcentral.com/articles/10.1186/s13104-022-06085-1

A bib file is available here:

https://github.com/neelsoumya/dsSurvival/blob/main/CITATION.bib


```bibtex
@article{Banerjee2022,
author = {Banerjee, Soumya and Sofack, Ghislain and Papakonstantinou, Thodoris and Avraam, Demetris and Burton, Paul and Z{\"{o}}ller, Daniela and Bishop, Tom RP},
doi = {10.1101/2022.01.04.471418},
journal = {bioRxiv},
month = {jan},
pages = {2022.01.04.471418},
publisher = {Cold Spring Harbor Laboratory},
title = {{dsSurvival: Privacy preserving survival models for federated individual patient meta-analysis in DataSHIELD}},
year = {2022}
}
```



## Bookdown

The complete bookdown, tutorial, vignette with executable code and synthetic data is available here:

https://neelsoumya.github.io/dsSurvival2bookdown/




## Quick start

Please install R and R Studio 

   https://www.rstudio.com/products/rstudio/download/preview/


Install the following packages:


```r

install.packages('devtools')
library(devtools)
devtools::install_github('neelsoumya/dsSurvivalClient')
devtools::install_github('datashield/dsBaseClient@6.1.1')
install.packages('rmarkdown')
install.packages('knitr')
install.packages('tinytex')
install.packages('metafor')
install.packages('DSOpal')
install.packages('DSI')
install.packages('opalr')

```


Follow the tutorial in bookdown format with executable code:

https://neelsoumya.github.io/dsSurvival2bookdown/




## Full Installation


* Install R and R Studio 

* In R, install the following packages

```r 
  
  install.packages('devtools')
  library(devtools)
  devtools::install_github('neelsoumya/dsSurvivalClient')
  install.packages('bookdown')
  devtools::install_github('datashield/dsBaseClient@6.1.1')
  install.packages('rmarkdown')
  install.packages('knitr')
  install.packages('tinytex')
  install.packages('metafor')  
  install.packages('DSOpal')
  install.packages('DSI')
  install.packages('opalr')
  
  ```

  or

  ```r 

  R --no-save < installer_R.R
  
  ```
  
  or
  
  run the following script in R `installer_R.R`
  
 
 Install R Studio and the development environment as described below:

    https://data2knowledge.atlassian.net/wiki/spaces/DSDEV/pages/12943461/Getting+started

 Install the virtual machines as described below:

    https://data2knowledge.atlassian.net/wiki/spaces/DSDEV/pages/931069953/Installation+Training+Hub-+DataSHIELD+v6
    

    https://data2knowledge.atlassian.net/wiki/spaces/DSDEV/pages/1657634881/Testing+100+VM


    https://data2knowledge.atlassian.net/wiki/spaces/DSDEV/pages/1657634898/Tutorial+6.1.0+100+VM

Install dsBase and dsSurvival on Opal server in the Virtual Machine (type neelsoumya/dsSurvival and main in the textboxes)
  
  
## Usage

See the bookdown below for a complete tutorial:

https://neelsoumya.github.io/dsSurvival2bookdown/



A minimal example of a book based on R Markdown and **bookdown** (https://github.com/rstudio/bookdown). 

The bookdown can be compiled by typing the following commands:

  ```r 
  
  library(bookdown)

  bookdown::serve_book()
  
  ```


## Contact

Soumya Banerjee and Tom R.P. Bishop

sb2333@cam.ac.uk


## Citation



If you use the code, please cite the following manuscript:

Banerjee S, Sofack G, Papakonstantinou T, Avraam D, Burton P, et al. (2022), dsSurvival: Privacy preserving survival models for federated individual patient meta-analysis in DataSHIELD, bioRxiv: 2022.01.04.471418.

https://www.biorxiv.org/content/10.1101/2022.01.04.471418v2

https://doi.org/10.1101/2022.01.04.471418

https://bmcresnotes.biomedcentral.com/articles/10.1186/s13104-022-06085-1

A bib file is available here:

https://github.com/neelsoumya/dsSurvival/blob/main/CITATION.bib


```bibtex
@article{Banerjee2022,
author = {Banerjee, Soumya and Sofack, Ghislain and Papakonstantinou, Thodoris and Avraam, Demetris and Burton, Paul and Z{\"{o}}ller, Daniela and Bishop, Tom RP},
doi = {10.1101/2022.01.04.471418},
journal = {bioRxiv},
month = {jan},
pages = {2022.01.04.471418},
publisher = {Cold Spring Harbor Laboratory},
title = {{dsSurvival: Privacy preserving survival models for federated individual patient meta-analysis in DataSHIELD}},
year = {2022}
}
```
