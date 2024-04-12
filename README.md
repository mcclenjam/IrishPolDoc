# IrishPolDoc: Irish internal party policy documents

## Description
This package was created to keep track of all those party policy documents published that are *not* alternative budgets or manifestos, but instead the documents created by political parties which give us a more detailed insight as to their
priorities. The aim of this package was to make these documents accessible to others in one place, as well as to form the basis of possible future research.

Information contained within the data-frame consists of; 
* *i*: a unique ID code for each document 
* *text*: the full text of the document
* *document_name*: full title of the document (per the political party)
* *party*: political party

Current internal Irish party policy documents for; 
* Fine Gael
* Fianna Fáil
* Sinn Féin
* Labour
* People Before Profit
* Green Party
* Social Democrats

Plan on adding documents from Aontú and Independent Ireland if/when they become available.



NB; I am by no means claiming this is an exhaustive database of internal party policy documents, but rather only those that are accessible to the public on these parties websites.

## Installation

The package is hosted on GitHub and not available at CRAN. To install
the latest development version:

``` r
if (!require("devtools")) {
    install.packages("devtools")
}
devtools::install_github("mcclenjam/IrishPolDoc") 
```

## Demonstration

``` r
# load packages
library(IrishPolDoc)

# load data
data(IrishPolDoc)
```
