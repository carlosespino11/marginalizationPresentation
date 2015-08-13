---
title: "Marginalization in Mexico"
author: "Carlos Espino"
date: "August 11, 2015"
output: ioslides_presentation
runtime: shiny
---



## Overview

* The purpose of this app is to make an analysis of social exclusion (marginalization) in Mexico. 
* Social exclusion is the process in which individuals or entire communities of people are systematically blocked from various rights, opportunities and resources that are normally available to members of a different group, and which are fundamental to social integration within that particular group.


* To make this analysis, we use some commonly used variables to measure marginalization. These are measured by state.
* The app includes a tools and visualizations to:
  + Visualize the marginalization variables.
  + Create an index with the desired marginalization variables and visualize it.
  + Create clusters and visualize them.


## Visualization tool

* The visualization tools allows the user to choose between the marginalization variables to visualize them as the following map:

<!--html_preserve--><iframe src="app8fefda594cf909966b4a3a3e33bb6c8a/?w=&amp;__subapp__=1" width="100%" height="500" class="shiny-frame"></iframe><!--/html_preserve-->



## Tool to create an index

* This tool helps to create an marginalization index. 
* This is a single number for each state that summarizes all the marginalization variables.
* A common way to do this is to perform a principal component analysis and use the first component as the index.
* The tool in the app gives the choice to the user to choose the desired values to create the index.



