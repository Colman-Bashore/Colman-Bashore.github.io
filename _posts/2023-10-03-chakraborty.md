---
title: "Disability and COVID-19 Reproduction"
excerpt_separator: "<!--more-->"
categories:
  - Studies
tags:
  - GIS
  - Reproduction
---

In Open Source GIScience we conducted a reproduction study of Chakarborty (2021) which focused on the intersection between disability and other demographic characteristics with COVID-19. Carrying out a reproduction study has made me realize just how challenging it is to follow the precise steps taken out by a previosu researcher even if they appear initially straightforward. I am learning that research studies are actually often quite vague when it comes to describing methodologies. I do think however, that conducting this study has caused me to look at research methodology with a closer eye. For my modification to the study I worked on editing some of the cartographic workflow to improve the visibility of the maps produced by the study and this allowed me to get more comfortable using the tmap package. My modification simplified the state borders and adjusted other linework on all of the maps to make them cleaner and more legible. The reproduction we carried out had a few planned and unplanned deviations. The deviations were mostly focused on creating better clusters for the GEE model that didn't center on relatively insignificant counties instead of local epicenters. I believe that these deviations improve the accuracy of the model because it weights more heavily those counties that are actually major COVID centers. I believe that the clustering and GEE model is the most confusing part of the study and further streamlining/simplifying the clustering process would be ideal, but I am unsure at this point how that could be carried out. The study claims that the results imply a correlation between PwD's and membership in a disadvantaged membership group with COVID-19 risk. I believe a meaningful study that would improve on this would focus on this issue on an individual or local level rather than a county level. It would also be interesting to examine similar patterns with other highly contagious diseases to investigate whether some of the same trends hold true. 

Link to [full report](https://colman-bashore.github.io/RPr-Chakraborty-2021/)

Link to [full repository](https://github.com/Colman-Bashore/RPr-Chakraborty-2021)

