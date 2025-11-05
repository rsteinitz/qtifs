
# Queer and Trans Field Safety Assessment
## A product of the Queer and Trans Inclusive Fieldwork Summit (QTIFS)

This repository contains the data and analysis code used in support of the manuscript:

**The Queer & Trans Field Safety Assessment: a tool for protecting minoritized field scientists.**  
*Authors: Amelia H. Reynolds¹, Evan Ho¹, Ronnie Steinitz², Mel Baldino³, Mar C. Arroyo⁴, Julian E. Fearon⁶, Paige V. Kouba¹, Nina A. Sokolov⁵, Rachel R. Carlson³, Sara Herrejon Chavez⁵, Kobie E. Boslough⁷, Amiel Flores⁷, and Allison Payne¹*

¹ Department of Ecology and Evolutionary Biology, University of California, Santa Cruz, CA, USA  
² Dian Fossey Gorilla Fund, Atlanta, GA, USA  
³ Department of Environmental Science, Policy, and Management, University of California, Berkeley, CA, USA  
⁴ Ocean Sciences Department, University of California, Santa Cruz, CA, USA  
⁵ Department of Integrative Biology, University of California, Berkeley, CA, USA  
⁶ Department of Earth and Planetary Sciences, University of California, Santa Cruz, CA, USA  
⁷ Department of Ecology and Evolutionary Biology, University of California, Los Angeles, CA, USA  

## Overview

The Queer and Trans Field Safety Assessment (QTFSA) is a structured checklist designed to support inclusive, identity-affirming field environments. This repository accompanies the manuscript and provides all reproducible code used for the literature review and quantitative analyses of field-safety recommendations.

The goal of the QTFSA is to translate broad calls for inclusion into actionable steps that can be implemented across labs, field courses, and field stations, bridging the gap between policy and practice in field safety.


## Repository contents

* `QTIFS lit review data Nov 2025.xlsx`: cleaned and coded literature review dataset.  

* `QTIFS-New-Nov-2025.Rmd`: reproducible R Markdown file containing all analyses and figures.  

* Generated plots (`.png`) and summary tables (`.csv`): figures and tables referenced in the manuscript.  


## Analysis summary

All analyses were conducted in **R 4.4.1 (RStudio 2025.05.1)** using `tidyverse`, `ggplot2`, and related libraries. The code quantifies the frequency and distribution of implementation plans across thematic categories (Climate, Protocols, Training, Accessibility) and scales of responsibility (Individual, PI, Lab, Department, Institution, Outside Institution).


## How to reproduce

* Clone or download this repository.

* Open `QTIFS-New-Nov-2025.Rmd` in RStudio.

* Ensure all required packages are installed (`tidyverse`, `ggalluvial`, `viridis`, `ggpubr`, `patchwork`, `janitor`, `readxl`, `scales`).

* Knit to HTML or PDF to reproduce all figures and tables.


## Citation

If you use or reference this work, please cite the corresponding manuscript once published:

*Reynolds A.H. et al. (2025). The Queer & Trans Field Safety Assessment: a tool for protecting minoritized field scientists. [Journal Name TBD].*

License and data availability

All code and data in this repository are made available under the **Creative Commons Attribution 4.0 International (CC BY 4.0) license**. Users are free to share and adapt the material with proper attribution to the authors.

