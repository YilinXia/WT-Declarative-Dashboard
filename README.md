# Declarative Dashboards for Volumetric Data

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/YilinXia/WT_Declarative_Dashboard/master?urlpath=lab/tree/widgyts_PR.ipynb)

## Project Overview
This project will explore developing a custom front-end for volumetric (i.e., astrophysical, oceanographic, weather, finite element) data accessible to Whole Tale. This will include developing a dashboard of analysis methods on these datasets, and utilizing existing open source libraries for exposing methods to individuals. The final result will be both a dashboard and a downloadable set of machine-readable representations of the current state of the dashboard, which can be re-ingested as a secondary tale.
 
## Repo Introduction
This repo will be used to store all the necessary files or scripts regarding the project described above.
 
**Milestone 1** Launch PR "dataset viewver" in Jupyter Lab with Voila

Here, we use binder (which containing repo2docker)to test our environement settings and later we will put all shell scripts from folder **"binder"** to set up the environment in WT.

## Voilà
Voilà turns Jupyter notebooks into standalone applications and you can find more dashboards on Voilà gallery.

**Challenges faced by Jupyter**
- not an ideal way to communicate with non-technical readers, who have to understand or re-execute the code to get insights
- security mode: users can interact with the noetbooks without arbitrary running code

**Voilà Advantages**
* supporting Jupyter interactive widgets
* Voilà does not permit arbitrary code execution by consumers of dashboards.
* Built upon Jupyter standard protocols and file formats, voilà works with any Jupyter kernel (C++, Python, Julia), making it a language-agnostic dashboarding system.
* Voilà is extensible. It includes a flexible template system to produce rich application layouts. 


## Reference
QuantStack. (2019, September 25). And voilà! Retrieved August 10, 2020, from https://blog.jupyter.org/and-voil%C3%A0-f6a2c08a4a93

## License


