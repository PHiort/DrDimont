# DrDimont: A Pipeline for Drug Response Prediction from Differential Analysis of Multi-omics Networks

## Installation of the package

1. Installing the R package
    - From CRAN: Use `install.packages("DrDimont")` to install the package and the R dependencies (NOT AVAILABLE YET)
    - From source: Either clone the repo and use `devtools::install()` within R to install the package, or use `remotes::install_gitlab("PHiort/DrDimont")` without cloning.
2. Installing the python dependencies
    - To use the differential drug response score computation, a Python (>= 3.8) installation is required. Once the DrDimont package is installed, use `DrDimont::install_python_dependencies()` to install the necessary dependencies automatically. You can use the function arguments to customize and use either pip or conda for the installation. If you prefer to install the dependencies manually, check out the requirements files in this repository `inst/requirements_pip.txt`, and `inst/requirements_conda.txt`.


## Exemplary Pipeline Execution
An exemplary pipeline execution with the included data can be found in `vignettes/DrDimont_Vignette.html`.
The supplied case study data uses data published by Krug et al. (2020) (https://www.doi.org/10.1016/j.cell.2020.10.036). The package license applies only to the software and explicitly not to the included data.

## Additional Information

At the moment all functions are exported to make debugging easier. However, many functions are not intended for user-interaction. These functions are marked with `[INTERNAL]` in the function documentation.


The package `DrDimont` is an updated version of the previously published `molnet` package (https://github.com/molnet-org/molnet; https://cran.r-project.org/web/packages/molnet/index.html)