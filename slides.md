Where R we?: An Introduction to the RStudio IDE and tips to getting you started on your reproducible research journey
========================================================
author: Heidi Steiner
date: Jan 14, 2022
autosize: true


Why RStudio?
========================================================



- Conveniently using the R language (but RStudio is not necessary!)
- Most popular R IDE (but others exist!)
- TONS of point-and-click options for common needs

Tour
========================================================



- File > New Project (check out "Good enough practices in scientific computing")
  - improved reproducibility and collaboration
- R Script
- Four Quadrants
- Setting to improve your experience


Packages
========================================================


- Units of code shared with the greater R community 
- Install in III, or

```r
install.packages("tidyverse")
```
- use in III, or

```r
library(tidyverse)
```


Import Data
========================================================

- Import in II, or 

```r
read.delim()
read_delim()
read_xls()
fread()
```
