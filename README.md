<p align="center">
  <img width="800" height="400" src="https://github.com/prislb/Pupillometry_Basics/blob/main/BannerInfo.png">
</p>

<div align="center"> <h1 align="center"> Pupillometry for Linguistics: The basics </h1> </div>

## Work supported by the National Science Foundation Dissertation Improvement Award awarded to Priscila López-Beltrán  
[![NSF-1939903](https://img.shields.io/badge/NSF-1939903-blue.svg)](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1939903&HistoricalAwards=false) 

## Go to Kaggle to view interactive versions of all 5 Notebooks associated with this repository
[![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/priscilalpezbeltrn/code)

## Launch the Binder for this project in JupytherLab + RStudio Server 
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/prislb/Pupillometry_Basics/main??urlpath=rstudio)

<p align="center">
  <img width="600" height="200" src="https://github.com/prislb/Pupillometry_Basics/blob/main/Rserver.png">
</p>

## **Materials in this repository**

![](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)

1. Pupillometry for Linguistics IPYNB files. Consist of 5 interactive notebooks covering diverse topics in pupillary data analysis. They can be     opened in Kaggle or downloaded and run in JupyterLab:

- Part I: Understanding Pupillometry ([open](https://www.kaggle.com/code/priscilalpezbeltrn/pupillometry-for-linguistics-parti))
- Part II: Creating a GAMMs model ([open](https://www.kaggle.com/code/priscilalpezbeltrn/pupillometry-for-linguistics-partii))
- Part III: Significance testing in GAMMs ([open](https://www.kaggle.com/code/priscilalpezbeltrn/pupillometry-for-linguistics-partiii))
- Part IV:  AR(1) autoregressive models ([open](https://www.kaggle.com/code/priscilalpezbeltrn/pupillometry-for-linguistics-partiv))
- Part V: Interactions in GAMMs ([open](https://www.kaggle.com/code/priscilalpezbeltrn/pupillometry-for-linguistics-partv))

2. Pupillometry for Linguistics Rmd file. This is a long file covering diverse topics in pupillary data analysis. This file can be run within an [IRkernel](https://irkernel.github.io/) in JupyterLab via RServer,

3. Pupillometry for Linguistics HTML files. Consist of HTML versions of all 5 notebooks in this repository for those who do not wish to deal with the hassle of downloading the data and running the scripts.

4. A CSV file with sample pupillometric data ([DOI](10.34740/kaggle/ds/2021248))

## **What is pupillometry?**

Pupillometry is an online data collection technique employed in language science research. Psychological and neurological work over the past several decades has shown that the pupillary response is linked not only to changes in ambient luminance, but also to aspects of language processing.

While the design of a pupillometric experiment is beyond the scope of this repository, the various files here below should provide a good first approach to analyzing pupillometric data. 

## **What can you learn using the materials in this repository?**

While the design of a pupillometric experiment is beyond the scope of this repository, the notebooks here should provide a good first approach to analyzing pupillometric data in R. 

## **Overview of the notebooks**
The series of 5 notebooks in this repository contain the basic principles needed to analyze pupillometic time-series data using *Generalized Linear Mixed Models* (GAMMs), which can be seen as regression models which are able to model *non-linear* patterns in data.  

The data (which can be donwloaded in the data branch of this repository using Git's [LFS](https://github.com/prislb/Pupillometry_Basics/tree/data) consists of pupillary dilation data recorded millisecond by millisecond as participants listened to Linguistic stimuli in a controlled experimental setting. All data were recorded using an [EyeLink Portable Duo](https://www.sr-research.com/eyelink-portable-duo/). For more information on this data, please visit my [Kaggle dataset repository](https://www.kaggle.com/datasets/priscilalpezbeltrn/pupillometry-sample).

The notebooks will guide the learner in the creation of progressively more complex GAMM models using the [mgcv](https://cran.r-project.org/web/packages/mgcv/index.html) R package. In addition, because visualization is crucial for significance testing in GAMMs, scripts will also be provided to visualize the data using the [itsadug](https://cran.r-project.org/web/packages/itsadug/index.html) R package. 

Using these packages, the reader will learn to create plots for fitted smooths and binary difference smooths, as seen below:

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

## **Disclaimers**
- These materiales are based on work funded by a National Science Foundation [Dissertation Improvement Award Grant BCS-1939903](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1939903&HistoricalAwards=false), awarded to Priscila López-Beltrán. 

- These materiales are based on work funded by [NSF PIRE II: Translating cognitive and brain science in the laboratory and field to language learning environments](https://pire.la.psu.edu/about/pire-ii-translating-cognitive-and-brain-science-research-to-the-field-of-education-settings), awarded to the Center for Language Science at The Pennsilvania State University.
