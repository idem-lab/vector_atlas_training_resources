[![Vector Atlas](images/vector-atlas-logo.png)](https://vectoratlas.icipe.org) <br> <br>

# Vector Atlas Training Resources Hub

This repository contains linkages to a curated set of **free** online resources for self-directed and mentored learning on data management, visualisation, basic spatial analysis and presentation, and modelling of mosquito disease vectors, tailored to collaborators of the **Vector Atlas**.

Most of these resources contain exercises you can do yourself along with the materials — the hub is heavy on practical materials.

The **Vector Atlas** has no oversight of the linked resources and takes no responsibility for their content — the list is intended only as a courtesy to our collaborators

The repository is roughly in order from introductory to more advanced, and the though each item is not necessarily a prerequisite for those that follow.

[Questions?](#questions)

### Resources

[**Data Management, Manipulation, and Presentation in R**](#data-management-manipulation-and-presentation-in-r)

[*Introduction to Spatial Analysis for Infectious Diseases*](#introduction-to-spatial-analysis-for-infectious-diseases)

-   [Data management](#data-management)
-   [Data Handling and Visualisation in R](#data-handling-and-visualisation-in-r)
-   [Spatial Data in QGIS (MAP)](#spatial-data-in-qgis-map)
-   [Spatial Data in R (MAP)](#spatial-data-in-r-map)

[*Introductory R Resources*](#introductory-r-resources)

-   [A Gentle Introduction to Tidy Statistics in R](#a-gentle-introduction-to-tidy-statistics-in-R)
-   [Getting Started with Data in R](#getting-started-with-data-in-r)
-   [RStudio Education](#rstudio-education)

[*Further R Learning*](#further-r-learning)

-   [R for Data Science](#r-for-data-science-2nd-edition)
-   [R Programming](#r-programming)
-   [Advanced R](#advanced-r)

[**Data Presentation**](#data-presentaition)

-   [Data Visualization: a Practical Introduction](#data-visualization-a-practical-introduction)
-   [ggplot2: Elegant Graphics for Data Analysis](#ggplot2-elegant-graphics-for-data-analysis-3rd-edition)

[**Working with Spatial Data**](#working-with-spatial-data)

[*Spatial Data in R*](#spatial-data-in-r)

-   [Spatial Data with `terra`](#spatial-data-with-terra)
-   [Simple Features for R](#simple-features-for-r)

[*Spatial Data in QGIS*](#spatial-data-in-qgis)

-   [Spatial Data in QGIS (MAP)](#spatial-data-in-qgis-map)
-   [Spatial Data in QGIS (QGIS)](#spatial-data-in-qgis-qgis)

[**Modelling Species' Distributions**](#modelling-species-distributions)

-   [Species Distribution Modelling](#species-distribution-modelling)
-   [Species Distribution Modelling for Vectors Course](#species-distribution-modelling-for-vectors-cours)
-   [Boosted Regression Trees](#boosted-regression-trees)

<br>

## Data Management, Manipulation, and Presentation in R

### Introduction to Spatial Analysis for Infectious Diseases

*Malaria Atlas Project* <http://malariaatlas.org/training>

This is a suite of introductory materials developed by the [Malaria Atlas Project](http://malariaatlas.org/), and covers many of the technical subject areas further below. The training materials are intended for an epidemiology audience, but entomological collaborators of the Vector Atlas will find strong cross-over and familiarity with the applications and skills. The materials are intended to be delivered through an in-person course, but can also be followed independently online.

The best place to begin is on the home page ([Before We Get Started](https://malaria-atlas-project.gitlab.io/intro-to-spatial-analysis-for-infectious-diseases/index.html)), which links to data, notes, and has installation instructions for the software used.

There are separate tutorials on:

#### Data management

<https://malaria-atlas-project.gitlab.io/intro-to-spatial-analysis-for-infectious-diseases/01_datamanagement.html>

#### Data Handling and Visualisation in R

<https://malaria-atlas-project.gitlab.io/intro-to-spatial-analysis-for-infectious-diseases/02_datahandling.html>

#### Spatial Data in QGIS (MAP)

<https://malaria-atlas-project.gitlab.io/intro-to-spatial-analysis-for-infectious-diseases/03_QGIS.html>

#### Spatial Data in R (MAP)

<https://malaria-atlas-project.gitlab.io/intro-to-spatial-analysis-for-infectious-diseases/04_spatial_in_R.html>

### Introductory R resources

We recommend R as a tool for the analysis of data. It is free, widely used, has many learning and support resources available, and can be very powerful. R is a programming-language based tool that does require a degree of up-front investment of time in learning to produce results and comfortably use the tool. For people who regularly want to manipulate or analyse data, and produce graphics, we suggest that this may be a worthwhile investment. We also produce R-based resources through our work in the Vector Atlas that can be easily reused and repurposed toward collaborators' specific needs.

#### A Gentle Introduction to Tidy Statistics in R

*Thomas Mock* <https://posit.co/resources/videos/a-gentle-introduction-to-tidy-statistics-in-r/>

This is a great starting point for learning about R. 1--hour video introduction to why and how you might do data analyses in R, and to how the whole system works (R, RStudio, packages). This is *not* an introduction to statistics, but an introduction to how to do some things in R. The slides are available on a linked github page - look for the pdf on that link. There is also a (slightly older) [blog version of the video here](https://themockup.netlify.app/posts/2018-12-10-a-gentle-guide-to-tidy-statistics-in-r/).\
*We strongly recommend to setting the video quality to the highest available so that you can clearly see the code in the video. This can be done by clicking the settings cog in the bottom-right of the video panel, and selecting Quality to 1080p.*

#### Getting Started with Data in R

*Chester Ismay and Albert Y. Kim* <https://moderndive.netlify.app/1-getting-started.html>

Step-by-step written introduction to getting started using R. This takes you through installing R and RStudio, some introductory concepts. This page is the first part of a longer [ebook that is also freely available](https://moderndive.netlify.app) and will walk you through further stages of learning to use R to produce graphs and basic statistical analyses.

#### RStudio Education

<https://education.rstudio.com>

A series of links to educational resources curated by RStudio — from beginner, to intermediate, and more advanced topics.

### Further R learning

#### R for data science (2<sup>nd</sup> edition)

*Hadley Wickham* <https://r4ds.hadley.nz>

This free ebook is a comprehensive guide to developing modern data science skills in R. It covers a wide range of methods for dealing with data — reading, writing, transforming, manipulating, and visualising. It does not teach modelling, but it does teach a range of foundational skills needed to get data into and out of models. This text also covers the `tidyverse` paackage, which is a ubiquitous group of R packages that have a consistent style of programming that is different from basic R, but widely considered more user-friendly.

#### R Programming

*Roger D. Peng* <https://www.coursera.org/learn/r-programming>

This is a popular R introductory to intermediate course and is free on Coursera from Johns Hopkins University. The course is a comprehensive foundation in fundamentals of base-R, but is a large commitment in time to complete and does not cover a number of modern areas of R-programming like `tidyverse`.

#### Advanced R (2<sup>nd</sup> edition)

*Hadley Wickham* <https://adv-r.hadley.nz>

This book is for users of R ready to advance toward and beyond an intermediate level, through a deeper understanding of the functioning of the R language, and advanced functional programming and beyond.

### Data presentation

#### Data Visualization: A Practical Introduction

*Kieran Healy* <https://socviz.co/>

An excellent transition from the very basics of making your first plots in R, through to advanced consideration of how to and why to use plots do best communicate your data, to advanced methods for tuning graphics.

#### ggplot2: Elegant Graphics for Data Analysis (3<sup>rd</sup> edition)

*Hadley Wickham* <https://ggplot2-book.org>

A walk-through of how to produce graphics in R using the popular `ggplot2` package. This book can be read as a learning resource, or used as a reference manual for working out specific problems or plot types.

## Working with spatial data

### Spatial Data in R

#### Spatial Data in R (MAP)

[Spatial Data in R (MAP)](#spatial-data-in-r-map)

#### Spatial data with `terra`

*Robert Hijmans and others* <https://rspatial.org/spatial/index.html#>

The `terra` package is the most powerful modern method to work with raster data in R (and replaces the deprecated `raster` package), and can also be used with vector\* data. This is a step-through guide to working with spatial data using `terra`. For a broader introduction to spatial data in R, this page forms just one section of [rspatial.org](https://rspatial.org), which has a wider range of resources that may be helpful for beginners in spatial data science.

\**Where we indicate * vector\* *with a *\* *we mean vector as a [spatial data form, i.e., points, lines, polygons](https://gisgeography.com/spatial-data-types-vector-raster/), not vector as in disease vector like a mosquito.*

#### Simple Features for R

*Edzer Pebesma* <https://r-spatial.github.io/sf/articles/sf1.html>

The `sf` or Simple Features package is another powerful modern tool for working with vector\* data in R. This guide explains what simple features are and the fundamentals of how the package works, but also [links to a series of increasingly detailed articles](https://r-spatial.github.io/sf/articles/) on the use of `sf`, as well as the package reference manual.

### Spatial Data in QGIS

#### Spatial Data in QGIS (MAP)

[Spatial Data in QGIS (MAP)](#spatial-data-in-qgis-map)

#### Spatial Data in QGIS (QGIS)

<https://docs.qgis.org/3.28/en/docs/user_manual/introduction/getting_started.html>

QGIS is a free, open-source, and well supported Geographic Information System in which users can manipulate and analyse spatial vector\* and raster data. This Getting Started article steps the user through installation and basic loading of data. It forms Chapter 5 of the full [QGIS User Guide](https://docs.qgis.org/3.28/en/docs/user_manual/index.html)

While analysis of spatial data in R is generally our recommendation because it is easily repeatable and modifiable, this does need the overhead of skill development to use R effectively, which may not always be practical for all users. QGIS is an excellent tool for quick plotting and exploration of spatial data and will suit many user needs.

## Modelling Species' Distributions

#### Species Distribution Modelling

*Robert Hijmans and Jane Elith* <https://rspatial.org/sdm/index.html>

A step-by-step guide to learn many good habits for species distribution modelling and how to practically do so in R, written by leading lights in the field. This guide takes you through all steps from the basic concepts, to data collection and preparation, to model fitting, evaluation and prediction.

The modelling method used in this guide is a relatively simple Generalised Linear Model, however the workflow that the guide teaches is vital to master before using other methods.

#### Species Distriubtion Modelling for Vectors Course

*Nick Golding and Gerry Ryan* <https://github.com/idem-lab/vector_sdm_course>

*Yes — here we mean disease vectors, not spatial ones*. This course is intended to be taught in person, and is focussed on developing understanding of key concepts around data biases and how they apply in particular to modelling the distribution of vectors. The course covers a range of modelling methods such as GLMs, MaxEnt, and Multispecies Poisson Point-Process models.

Although users may follow the course materials using the [broad course outline](https://github.com/idem-lab/vector_sdm_course/blob/master/course_structure.md) at present, we intend to update materials make it easier to follow-through independently as well.

#### Boosted Regression Trees

*Jane Elith and John Leathwick* <https://rspatial.org/raster/sdm/9_sdm_brt.html>

Boosted Regression Trees (BRTs) are a powerful method for fitting non-linear interacting relationships, including for modelling species' distributions. This is a guide to fitting BRTs using the `dismo` package in R. This guide is a companion to the very accessible journal articale [A Working Guide to Boosted Regression Trees](https://doi.org/10.1111/j.1365-2656.2008.01390.x), and jives well with the code from the Hijmans and Elith guide listed above. NB: the code in the final section, [Spatial Prediction](https://rspatial.org/raster/sdm/9_sdm_brt.html#spatial-prediction), is based on the deprecated `raster` package. It should work largely as-is by replacing `raster` with `terra` in the code.

#### Questions?

This page maintained by Gerry Ryan on behalf of the **Vector Atlas**.

If there are problems with the page or links are dead, please [post an issue](https://github.com/idem-lab/vector_atlas_training_resources/issues).

Other questions? Please contact us at [vector.atlas\@biology.ox.ac.uk](mailto:vector.atlas@biology.ox.ac.uk){.email}

[![Vector Atlas](images/vector-atlas-logo.png)](https://vectoratlas.icipe.org) <br>
