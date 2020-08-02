# Hugo Book Too Theme

A work-in-progress, minor (hopefully someday major) edit of the great [hugo-book theme](https://github.com/alex-shpak/hugo-book).  

This fork is originally meant for creating R-based online books for class using [blogdown](https://bookdown.org/yihui/blogdown).  
For a lightweight blog theme, have a look at [hugo-valpro](https://github.com/egenn/hugo-valpro).

# Usage

Install blogdown, if you don't have it already:
```r
remotes::install_github('rstudio/blogdown')  
```
Create a new blogdown RStudio project and type in "egenn/hugo-valpro" for theme.  

Or, within some (new) project:

```r
blogdown::new_site(theme = 'egenn/hugo-booktoo')
```

For more documentation, take a look at the "themes" section in Yihui's [blogdownbook](https://bookdown.org/yihui/blogdown/themes.html)