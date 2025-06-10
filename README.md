# Data Analysis Using R

* Data Analysis Courses https://utah.catalog.instructure.com/browse/ds-learn/

## Introduction to R

* Install RStudio
* https://posit.cloud/
* Navigating RStudio and Quarto
  * Code in console
  * Quarto document
  * render documents
  * run code chunks
  * Source and Visual studio editor
* Objects in R
  * Projects, working directories, and defining objects/variables in R
    * create a new project
    * create a new quarto document
    * `x <- 1`
    * quarto document header `embed-resources: true` 
  * Best practices for reproducibility: Workspace image
    * Don't save workspace image (start fresh each time)
  * Working with objects/variables
    * order of code execution
  * Types
    * numeric
    * character
    * logical (TRUE FALSE)
    * class()
  * Type conversions
    * `as.character()` `as.logical()` `as.numeric()`
  * Logical operations
  * Objects and types
* Vectors
  * Introduction to vectors
  * Working with vectors and vectorization
  * Subsetting vectors
  * Integer sequence vectors
  * Logical subsetting
  * Vectors
* Loading data into R
  * Introduction to data frames
  * Loading .csv data files into R
  * Loading excel files and installing packages
  * 
* Working with dataframes using dplyr and the tidyverse
  * Subsetting data frames in "base R"
  * Extracting columns using the select() dplyr function
  * Chaining functions together with the pipe |>
  * Filtering rows using the filter() dplyr function
  * Adding/modifying columns using the mutate() dplyr function
  * Summarizing columns using the summarize() dplyr function
  * More grouped operations with the group_by() 
* Data visualization with ggplot2
  * Ggplot2 setup
  * Introction to ggplot2 with scatterplots
  * specifying aesthetics
  * creating line plots
  * Boxplots, histograms, adn layering geoms
  * Customizing ggplot2
  * Ggplot2 practice
