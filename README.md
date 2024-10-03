# sinasc

Author: Luan Augusto - EBSERH Technology Initiation Scholarship

e-mail: [luanguto87\@gmail.com](mailto:luanguto87@gmail.com)

## Introduction

`sinasc` is a R package created to automate the data extraction, cleaning and transformation from the SINASC - DATASUS.

SINASC is the name of the Information System about Live Births and DATASUS is name of the Department of Information of Brazil's Health Care System (Sistema Único de Saúde - SUS).

This package is one of the main activities of the EBSERH Technology Initiation Scholarship.

## Functions

-   `download.sinasc` is the primordial function of this package. This function is responsible to download the data from the DATASUS FTP Directory. The user enters with the year and the state they want and the output is a data frame with the raw information.

-   `label.sinasc` needs a data frame created by the function `download.sinasc` and this function is responsible to choose the util columns, clean the data and replace the code by the respective labels.

## Installation

The package can be istalled using the `devtools` library:

```         
devtools::install_github("luanaugusto05/sinasc")
```

## Contact Info

If you have any questions, please contact me at [luanguto87\@gmail.com](mailto:luanguto87@gmail.com).
