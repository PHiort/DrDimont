# Current package version
## Submission - version 0.1.5
In this version we have:
* fixed minor bugs
* updated the vignette and function descriptions
* updated graph generation to work with the new version of igraph (generate_individual_graphs() and subsidiary functions)
* updated the example data to new igraph format
* removed internal variables that are no longer needed
* removed Rd files of all internal functions

## Test environments
* local macOS Sonoma 14.8.1, R release (4.5.1), aarch64-apple-darwin20
    * OK
* R winbuilder R-release (4.5.1), R-devel
    * OK

## R CMD check results
0 errors | 0 warnings | 0 notes

## Downstream dependencies
There are currently no downstream dependencies for this package.


# Old package versions

## Submission - version 0.1.4
In this version we have:
* updated the vignette and function descriptions.
* updated the install_python_dependencies function.

## Test environments
* local Windows 10 Home 21H2, R release (4.1.3), x86_64-w64-mingw32 (64-bit)
    * OK
* local macOS Catalina 10.15.3, R release (4.1.3), x86_64-apple-darwin17.0 (64-bit)
    * OK
* R winbuilder R-release (4.2.1), R-devel
    * OK

## R CMD check results
0 errors | 0 warnings | 0 notes

## Downstream dependencies
There are currently no downstream dependencies for this package.

## Resubmission 3 - version 0.1.3
This is a resubmission. In this version we have:
* reduced the length of the title.
* removed redundant blank spaces in the description.
* added description of return values for all functions also ones without values to return.
* replaced dontrun{} with donttest{} for examples with longer runtimes or dependencies on python.
* set tempdir() as default for saving intermediate data for data exchange between R and python.

## Resubmission 2 - version 0.1.2
This is a resubmission. In this version we have:
* changed the LICENSE file to the CRAN format

## Resubmission 1 - version 0.1.1
This is a resubmission. In this version we have:
* reduced the data for the example computed with compute_correlation_matrices() to reduce the run time.

## Submission - version 0.1.0

## Test environments
* local Windows 10 Home 21H2, R release (4.1.3), x86_64-w64-mingw32 (64-bit)
    * OK
* local macOS Catalina 10.15.3, R release (4.1.3), x86_64-apple-darwin17.0 (64-bit)
    * OK
* R winbuilder R-oldrelease (4.1.3), R-release (4.2.0), R-devel
    * OK

## R CMD check results
0 errors | 0 warnings | 1 note

* NOTE:
    * Maintainer: 'Katharina Baum <katharina.baum@hpi.de>'
    * This is a new release.

## Downstream dependencies
There are currently no downstream dependencies for this package.