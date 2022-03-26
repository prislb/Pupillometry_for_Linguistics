<p align="center">
  <img width="800" height="400" src="https://github.com/prislb/Pupillometry_Basics/blob/main/BannerInfo.png">
</p>

<div align="center"> <h1 align="center"> Pupillometry for Linguistics: The basics </h1> </div>

## Work supported by the National Science Foundation Dissertation Improvement Award awarded to Priscila López-Beltrán  [![NSF-1939903](https://img.shields.io/badge/NSF-1939903-blue.svg)](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1939903&HistoricalAwards=false) 

## Launch the Binder for this project in JupytherLab + RStudio Server [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/prislb/Pupillometry_Basics.git/main??urlpath=rstudio)

## Launch the Kaggle Notebook associated with this repository [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/priscilalpezbeltrn/pupillometry-for-linguistics)

**1. What is pupillometry?**


Pupillometry is an online data collection technique employed in language science research. Psychological and neurological work over the past several decades has shown that the pupillary response is linked not only to changes in ambient luminance, but also to aspects of language processing.

While the design of a pupillometric experiment is beyond the scope of this repository, the various files here below should provide a good first approach to analyzing pupillometric data. 

**2. What can you learn using the materials in this repository?**


While the design of a pupillometric experiment is beyond the scope of this repository, the notebooks here should provide a good first approach to analyzing pupillometric data in R. 

<p align="center">
  <img width="600" height="200" src="https://github.com/prislb/Pupillometry_Basics/blob/main/Rserver.png">
</p>


### Materials in this repository
1. Pupillometry for Linguistics HTML file.
2. Pupillometry for Linguistics Rmd file.
3. Pupillometry for Linguistics IPYNB file.
4. CSV file with sample pupillometric data ([DOI](10.34740/kaggle/ds/2021248))

![](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)

*Note: The IPYNB file can be easily opened in JupyterLab and run using [IRkernel](https://irkernel.github.io/)*

## Overview of the notebooks
This notebook contain the basic principles needed to analyze pupillometic time-series data using *Generalized Linear Mixed Models* (GAMMs), which can be seen as regression models which are able to model *non-linear* patterns in data.  

The data (which can be donwloaded in the data branch of this repository using Git's [LFS](https://github.com/prislb/Pupillometry_Basics/tree/data) consists of pupillary dilation data recorded millisecond by millisecond as participants listened to Linguistic stimuli in a controlled experimental setting. All data were recorded using an [EyeLink Portable Duo](https://www.sr-research.com/eyelink-portable-duo/).

Throughout the notebook, progressively more complex GAMM models will be created using the [mgcv](https://cran.r-project.org/web/packages/mgcv/index.html) R package. In addition, because visualization is crucial for significance testing in GAMMs, extensively explained code will be provided to visualize the data using the [itsadug](https://cran.r-project.org/web/packages/itsadug/index.html) R package. 

Using these packages, the reader will learn to create fitted smooths and difference smooths as seen below:



<div class="column">
          <p>Fitted Smooths</p>
        <img src="https://github.com/prislb/Pupillometry_Basics/blob/main/fitted%20smooth.jpeg" height="200" width="400"/>
    </div>
<div class="column">    
        <p>Difference Smooths</p>
        <img src="https://github.com/prislb/Pupillometry_Basics/blob/main/diff%20smooths.png" height="200" width="400"/>
    </div>
</div>

<br>

Finally, the reader will also learn how to visualize interactions between continuous variables in GAMMs using contour plots:
<div class="column">    
        <img src="https://github.com/prislb/Pupillometry_Basics/blob/main/contour.png" height="300" width="400"/>
    </div>
</div>

## Disclaimers
- These materiales are based on work funded by a National Science Foundation [Dissertation Improvement Award Grant BCS-1939903](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1939903&HistoricalAwards=false), awarded to Priscila López-Beltrán. 

- These materiales are based on work funded by [NSF PIRE II: Translating cognitive and brain science in the laboratory and field to language learning environments](https://pire.la.psu.edu/about/pire-ii-translating-cognitive-and-brain-science-research-to-the-field-of-education-settings), awarded to the Center for Language Science at The Pennsilvania State University.
