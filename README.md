# CBASSED50

The CBASSED50 R package to process CBASS-derived PAM data. Minimal requirements are PAM data (or data from any other continous variable that decreases with temperature, e.g. relative bleaching scores) from 4 fragments subjected to 4 temperature profiles of at least 2 colonies from 1 coral species from 1 site. Please refer to the [CBASS method paper] (https://aslopubs.onlinelibrary.wiley.com/doi/10.1002/lom3.10555) for in-depth information regarding CBASS acute thermal stress assays, ED50 thermal thresholds, etc. 

# Get Started

To get started download [CBASSED50_demo.qmd](https://github.com/greenjune-ship-it/CBASSED50/blob/main/CBASSED50_demo.qmd). The GitHub allows to do this directly from the web interface:

<p align="center">

<img src="https://github.com/greenjune-ship-it/CBASSED50/assets/83506881/b6c9f376-f4b6-46f8-87c2-dce0ccb50ad3"/>

</p>

This is a document with notebook interface that contains explanatory text together with the code.

# Contributing

If you want to contribute to a project and make it better, your help is very welcome.

You can always report an [issue](https://github.com/greenjune-ship-it/CBASSED50/issues) or fork this repository, implement/fix your feature and create a pull request.

# FAQ

### Error installing package 'mvtnorm'

In Ubuntu you may face the issue with 'mvtnorm' dependency installation.

To solve it, install the following libraries:

```         
sudo apt-get install gfortran
sudo apt-get install liblapack-dev libblas-dev
```

# User Support

You can always report the GitHub [issue](https://github.com/greenjune-ship-it/CBASSED50/issues) or email the current maintainer: [yulia.iakovleva\@uni-konstanz.de](mailto:yulia.iakovleva@uni-konstanz.de).
