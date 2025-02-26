# Installation Guide

Install from GitHub
To install the syntheticDatasets package directly from GitHub, use the following commands in R:

```
# Install remotes package if not already installed
install.packages("remotes")

# Install syntheticDatasets from GitHub
remotes::install_github("AditiGajjar/syntheticDatasets")
```

## Install Locally
If you have the package source files downloaded, you can install it manually:

```
# Set your working directory to the package source location
setwd("path/to/syntheticDatasets")

# Install the package
install.packages(".", repos = NULL, type = "source")
```

## Load the Package
After installation, load the package into your R session:

```
library(syntheticDatasets)
```


