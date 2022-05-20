## Resubmission 4
This is a resubmission. In this version we have 
* added the missing description of return values for the documentation of pipe() (sorry!)
* updated an outdated documentation of compute_correlation_matrices()
* corrected small errors in datasets individual_graphs_example, combined_graphs_example, correlation_matrices_example

## Resubmission 3
This is a resubmission. In this version we have:
* reduced the length of the title.
* removed redundant blank spaces in the description.
* added description of return values for all functions also ones without values to return.
* replaced dontrun{} with donttest{} for examples with longer runtimes or dependencies on python.
* reduced runtime of one offending example and removed dontrun{} for it
* corrected datasets metabolite_data and layers_example
* set tempdir() as default for saving intermediate data for data exchange between R and python.

## Resubmission 2
This is a resubmission. In this version we have:
* changed the LICENSE file to the CRAN format

## Resubmission
This is a resubmission. In this version we have:
* reduced the data for the example computed with compute_correlation_matrices() to reduce the run time.

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