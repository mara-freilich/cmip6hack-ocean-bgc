[![nbviewer:results](https://img.shields.io/badge/nbviewer-results-orange)](https://nbviewer.jupyter.org/github/mfreilich1/cmip6hack-ocean-bgc/blob/master/notebooks/final_analysis.ipynb)
[![Binder](https://binder.pangeo.io/badge_logo.svg)](https://binder.pangeo.io/v2/gh/mfreilich1/cmip6hack-ocean-bgc/master?filepath=notebooks%2Ffinal_analysis.ipynb)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3559209.svg)](https://doi.org/10.5281/zenodo.3559209)
[![License:MIT](https://img.shields.io/badge/License-MIT-lightgray.svg?style=flt-square)](https://opensource.org/licenses/MIT)

# CMIP6 Ocean Biogeochemistry

## Introduction:
This project examines historical simulations and future projections of ocean carbon uptake and storage in the CMIP6 ensemble, and explore their impacts on marine ecosystems drivers, with a focus on primary productivity. We have chosen to showcase some of the results that focus on air-sea fluxes of carbon as well as the spatial structure of ocean oxygen content. This analysis can be seen in the python notebook titled 'final_analysis'. Other analyses that were not prepared for presentation are in the notebooks in the 'raw' folder.

## Questions:
Overall, the hacking explored:

1. How do models simulate carbon and heat uptake compared to available observations? What are future projections under different ssp’s? what regions dominate carbon and heat uptake vs. storage? What are differences across models (uptake rates, regional differences, etc.) and what processes might explain these differences?

2. How well do models simulate the mean distribution and long-term trends of ecosystem drivers (SST, pH/aragonite saturation depth, [O2]/hypoxic depth, NPP) compared to available observations? Can we identify persistent or new biases since CMIP5? What are CMIP6 projections for marine ecosystem drivers in a warming climate? What are spatial characteristics, timescales of emergence, and differences across models? Is there a relationship between models’ carbon and heat uptake efficiency and the severity of their projected impacts on these ecosystem drivers? How did increased climate sensitivity since CMIP5 in certain models (e.g. CESM2) influence these impacts in these models?

3. Projections of NPP especially showcase major differences across CMIP5 models in sign and amplitude over important ocean regions (Eastern/central tropical Pacific, Subpolar gyres, etc. Fig 5. Bopp et al 2013). Does this spread still exist in CMIP6? Do projected changes in carbon export at depth mirror the changes in NPP? What physical and biogeochemical processes explain NPP and carbon export changes across regions and models (e.g. changes in easterlies, upwelling, nutrient transport by the EUC or the overturning circulation, stratification and ventilation, remineralization rates, etc.)?

We prioritized developing efficient workflows for loading, analysis, and plotting of model outputs and comparison to observations, and aimed for process-based examination of model projections, inter-model differences, and model biases.
