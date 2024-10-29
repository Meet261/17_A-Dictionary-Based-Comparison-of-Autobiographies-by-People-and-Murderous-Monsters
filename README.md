# 17_A-Dictionary-Based-Comparison-of-Autobiographies-by-People-and-Murderous-Monsters

https://mybinder.org/v2/gh/Meet261/17_A-Dictionary-Based-Comparison-of-Autobiographies-by-People-and-Murderous-Monsters/HEAD
Launch Online [![Binder](https://mybinder.org/badge_logo.svg)](https://notebooks.gesis.org/binder/v2/gh/Meet261/17_A-Dictionary-Based-Comparison-of-Autobiographies-by-People-and-Murderous-Monsters/HEAD)

Here is the markdown code for the dependency tracker of the 17th file, which I named `autobiographies_comparison.R`:

| **Serial Number** | **File Name**                       | **Dependencies**                                                                                  | **Reproducibility Status** | **Issue/Obstacle**                                                                                                                                                                        |
|-------------------|------------------------------------|---------------------------------------------------------------------------------------------------|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 17                | `analysis.R`     | `r-devtools`, `r-reshape2`, `r-sentimentr`, `r-lexicon`, `r-tidyverse`, `r-knitr`, `r-rmarkdown`   | Not Reproducible           | The installation of the `devtools` package fails with errors related to missing shared objects (e.g., `libicui18n.so.58`), which prevents the rest of the script from running successfully. |
