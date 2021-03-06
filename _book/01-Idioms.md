

# (PART) Idioms {-} 

# Idioms

## The four basic principles to a tidy API 

These principles are likely to change. This version is from January 1st 2016.

### Reuse existing data structures.

* try to use existing common base R structures instead of new customized ones
* if the latter is not possible create S3 classes based on a base R atomic or list
* use data frames or tibbles for rectangular data made up of observations and variables in rows and columns (which is basically tidy data)
* for "non-standard scoping", prefer formulas over non-standard evaluation and use the [lazyeval](https://github.com/hadley/lazyeval) package.

### Compose simple functions with the pipe.

### Embrace functional programming.

### Design for humans.


## Resources

* [The tidy tools manifesto](https://cran.r-project.org/web/packages/tidyverse/vignettes/manifesto.html)
