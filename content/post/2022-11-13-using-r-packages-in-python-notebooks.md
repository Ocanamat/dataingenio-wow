---
title: Using R packages in Python notebooks
subtitle: ""
summary: ""
description: ""

date: 2022-11-13T17:43:19.629Z

draft: true
feedback: true
preview: ""

tags: ""
categories: ""

authors: ""
authors_notes: ""

# Show the page's date?
show_date: true

# Show estimated reading time?
reading_time: true

# Show social sharing links?
share: true

# Show author profile (photo and bio) under the content?
# Edit your author profiles in the `content/authors/` folder
# Then reference their folder names with the `authors` front matter option above
profile: true

# Allow users to comment on the page?
# Requires commenting to be configured in `params.yaml`
commentable: false

# Allow visitors to make improvements to the page?
# Requires a repository to be configured in `params.yaml`
editable: false

# Show a link to the next article in the series?
pager: true

# Show recommendations for related content?
show_related: true

# Show breadcrumb navigation?
show_breadcrumb: true

# Hide the navigation bar?
# Often used together with `show_breadcrumb`
header:
  navbar:
    enable: false

lastmod: 2022-11-15T12:44:49.121Z
---

# Using R Packages in Python Notebooks

It is often the case that while coding an analysis on Python we wish to implement some functionality, or call a given service, only to discover through a quick Google search that there is a perfect `R` package that does what we need, but neither `pip` nor ==anaconda/conda-forge or github provides us with a comparably good solution.

For me was calling and using `R`'s wonderful `eurostat` package[^1]. `giscoR`[^2] is also another great better-in-R package example. Importing standard NUTS regions boundaries for a geospatial analysis notebook is better implemented in this package than on any other in python.

But how to get it working in a python notebook? Through the python `rpy2` package

## Preparation
Before jumping to cutting and pasting commands, you need to do the following:

* In windows:
  1. Create the following system variables:
      * `R_USER` : 
      * `R_HOME` :
      * `R_USER_LIBS` : 

![System Variables in Windows](../../assets/media/20221115-SysVars.png)  

* In linux:

## rpy2 package


## rwrap package


## All together




[^1]: [Tools for Eurostat Open Data - eurostat (ropengov.github.io)](https://ropengov.github.io/eurostat/)
[^2]: [rOpenGov/giscoR: Download geospatial data from GISCO API - Eurostat (github.com)](https://github.com/ropengov/giscoR)

