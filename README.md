# ICME Summer Short Course on R, 2016

## Schedule for the Day

### Session 1: 9 - 10:30
- [x] **Basic R.**

### Session 2: 10:45 - 12
- [x] **Plotting in R (`base` `ggplot2`, `plotly`)**
- [x] **Heatmaps in R (`heatmaply`)**

### Session 3: 2 - 3:15
- [x] **Apply functions in R.**

### Session 4: 3:30 - 4:45
- [x] **Statistical applications in R**

## References for further learning.
We provide as reference a list of packages and reference
materials for which we recommend for further learning.

- Package `dplyr` has a fantastic [tutorial](https://cran.rstudio.com/web/packages/dplyr/vignettes/introduction.html). This package is written by [Hadley Wickham](http://hadley.nz/) and aims to make
data manipulation easier in R.

- Package `ggmap` is built by Hadley as well as David Kahle to facilitate visualizing geo-spatial data. Their [original paper](https://journal.r-project.org/archive/2013-1/kahle-wickham.pdf).

- If you find yourself performing any simulations, Monte Carlo, or other embarassingly parallel operations, package `parallel` has a nice [tutorial](https://stat.ethz.ch/R-manual/R-devel/library/parallel/doc/parallel.pdf).

- My *personal favorite* package is `data.table`, written by Mathew Dowle. Here's a  [nice introduction](https://cran.r-project.org/web/packages/data.table/vignettes/datatable-intro.pdf).

- I also highly recommend Hadley's [Advanced R](http://adv-r.had.co.nz/) tutorial, which goes into many interesting details of how R is designed.

### For instructors, a quick reminder.
"I want to make a new change to the file! What do I do?"

1. Make sure you're up to date
  * `git checkout master`
  * `git fetch origin`
  * `git pull`
2. Make a new branch
  * `git checkout -b new-loss-function`
3. Do your thing
  * Write write write
  * `git add the-file.rmd`
  * `git commit -m "Added new loss function"`
  * `git push origin new-loss-function`
4. Merge it in!
  * Go to GitHub webpage
  * Compare and pull your branch (big green button at top)
  * Make sure you're good to merge
  * Merge and delete branch
