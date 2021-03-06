---
title: 'Installing R and RStudio'
---





## Installation {- #installation-intro}


#### RStudio Server {- #rstudio-server}

The simplest way to get started with RStudio is to get an account on a server installation of the software (if you are a Plymouth University student please see the guidance on the DLE).




#### Installing on your own machine. {- #local-install}


1. [Download RStudio 1.01 or later](https://www.rstudio.com/products/rstudio/download/) (I'd suggest using whatever version is most recent and upgrading as new versions become available because the software is fairly actively developed).

2. Install the [packages listed below](#dependencies)

3. If you want to 'knit' your work into a pdf format, you should also install LaTeX. On [windows use this installer](https://miktex.org/download). Make sure to do a 'full install', not just a basic install. On a Mac install [homebrew](https://brew.sh) and type `brew cask install mactex`.




#### Package dependencies {- #dependencies}

As noted, this guide uses a number of recent R packages to make learning R simpler and more consistent. This requires that the packages are installed first.

To install some of the recommended packages you will need a working C compiler (XXX Although perhaps not on Windows?). 

[This script](requirements.R) installs all dependencies on a recent Linux or Mac system. 





