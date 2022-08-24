### Geocomputation with R’s guide to reproducible spatial data analysis

**2022-08-30, OpenGeoHub Summer School 2022, Siegburg**

**Equipment and software requirements**

Attendees are expected to have a working version of R (version 4.1 or higher) and RStudio (version 2022 or higher) installed.

R and RStudio are supported by PC, Linux, and macOS and can be downloaded for free by following these links https://cloud.r-project.org/ and https://www.rstudio.com/products/rstudio/download/#download.

Additionally, we will use the Git software. The recommended way to install Git on Windows can be found at https://gitforwindows.org/. Installation instructions for macOS can be found at https://happygitwithr.com/install-git.html#macos. The Linux version can be installed using the following line of code:

```
# Ubuntu
sudo apt install git

# Fedora
sudo dnf install git
```

**R packages**

Run the code below in R to install all of the required R packages.

```r
install.packages("remotes")
pkg_list = c("terra", "sf", "tmap", "supercells", "dplyr",
             "usethis", "reprex", "renv", "devtools")
remotes::install_cran(pkg_list)
remotes::install_github("wmgeolab/rgeoboundaries")
```

Let me know if you have any questions! 
See you soon in Germany!