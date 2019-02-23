# Introduction to the tidyverse: dplyr, tidyr and purrr

This repo contains the slides, code, examples, and exercices used during the workshop that took place in Barcelona, the 4th February 2019, within the SIBECOL conference. The slides used during the course can be found [here](index.html), and the document with the exercises can be found [here](R/workshop_exercices.html).

## Content
In the last few years, the `tidyverse` has changed the way in which many scientist do data science. The tidyverse is a collection of R packages specifically designed for data science. All packages share an underlying design philosophy, grammar, and data structures, which has turned them into a kind of "own ecosystem" that some researchers have not dared to enter into. This workshop aims to overcome these fears by presenting some of the most widely used packages in the tidyverse: dplyr, tidyr and purrr. [tidyr](tidyr.tidyverse.org) has been specifically designed to organize and format data in a way that makes it easier to work with. [dplyr](dplyr.tidyverse.org) is designed to make the main data manipulation operations easier. Together, they facilitate data wrangling and enable the researcher to focus on the problems he or she wants to solve, not on how to solve them. [purrr](purrr.tidyverse.org), on the other hand, facilitates repetitive tasks and loops in tidy data by providing a complete and consistent set of tools for working with functions and vectors. 


## Dependencies
To follow the workshop you need to have the `tidyverse` package installed in your computer. Alternatively, you can also install the three components of the tidyverse that we will actually use during the workshop: `tidyr`. `dplyr`, and `purrr`. If you haven't installed them yet, you can do it by typing in your `R` console:

```
install.packages("tidyr")
install.packages("dplyr")
install.packages("purrr")
```

## Licence
The data needed to follow the workshop has been obtained from the 2nd and 3rd editions of the Spanish National Forest Inventory (Ministerio de Medio Ambiente, 2005), and can be found [here](https://github.com/ameztegui/tidyverse_workshop/tree/master/data)). All data, code and any associated documents are published under a MIT license, which allows any use, distribution or modification, provided authorship is acknowledged. Details can be found in the file [LICENSE.txt](LICENSE.txt). 

## Attribution and contact
If you use or modify the material in this repository, please cite it adequately as:

```
Ameztegui, A; Granda, V. (2019) Introduction to the tidyverse: dplyr, tidyr and purrr . 
GitHub repository, https://github.com/ameztegui/tidyverse_workshop
```
You can find more details in the file [CITATION.txt](CITATION.txt). For any use that goes beyond that license or for any doubt, please contact Aitor Ameztegui (ameztegui@gmail.com).

