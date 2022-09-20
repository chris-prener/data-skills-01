# data-skills-01

## Lesson Overview

### Objectives
At the end of this lesson, participants should be able to:

1. Demonstrate how basic objects, like data frames, are created and explored
2. Explain how functions, arguments, and packages fit together in `R`'s ecosystem
3. Demonstrate how to get help from within `R`
4. Describe what an `.Rproj` (R project) is in basic terms

### Lesson Resources
* The [`SETUP.md`](SETUP.md) file contains a list of packages required for this lesson
* The [`notebook/`](/notebook) directory contains both the seminar and completed versions of our lesson notebooks

### Extra Resources
* [RStudio cheatsheet](https://www.rstudio.com/resources/cheatsheets/#ide)
* [*R for Data Science*](http://r4ds.had.co.nz)

## Access Lesson
### Initial Package Installation
We use the `install.packages` function to install modular components of the `R` ecosystem. For instance, to access lesson materials, we'll use the `usethis` package. To install it, we run the following function in our console:

```r
install.packages("usethis")
```

### Download Lesson Materials
With the package installed, you you can download this lesson to your Desktop easily using `usethis`:

```r
usethis::use_course("https://github.com/chris-prener/data-skills-01/archive/master.zip")
```

By using `usethis::use_course`, all of the lesson materials will be downloaded to your computer, automatically extracted, and saved to your desktop. The `data-skills-01-master` project should open automatically afterwards.

### Install Other Packages for Today
In addition to `usethis`, there are a couple of other packages we'll need:

```r
install.packages(c("cowsay", "palmerpenguins", "knitr", "rmarkdown"))
```

Now we're ready to go!

## Contributor Code of Conduct
Please note that this project is released with a [Contributor Code of Conduct](.github/CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.