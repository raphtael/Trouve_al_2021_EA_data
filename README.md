# Trouve_al_2021_EA_data

This repository contains data used in the statistical analyses of the paper "The effect of species, size, and fire intensity on tree mortality within a catastrophic bushfire complex" by Trouve et al. (2021), published in Ecological Applications.
The data has been made available for reproducibility purposes, as required by Ecological Applications. 

The tree_mortality_status.csv file contains tree-level inventory data necessary to run the mortality model (Eq. 1) presented in the manuscript. Column names are  explained below.

* plot_id: Unique identifier for each plot.
* species: Species name associated with each measured tree.
* spp_code, Species code associated with each measured tree.
* dbh_cm: Diameter at breast height associated with each measured tree.
* top_kill: Binary variable indicating whether the tree is top-killed or not (0: alive, 1: top-killed). We distinguished between trees that had been top-killed but were resprouting from the base and those that were completely killed (i.e., no evidence of basal resprouting). The former was recorded as top-kill, the latter as full-kill.
* full_kill: Binary variable indicating whether the tree is full-killed or not (0: alive or top-killed, 1: full-killed).

The plot_metadata.csv file contains plot-level metadata associated with each plot as well as some information on the estimated mean relative latent fire intensity and regeneration mesurements per plot.
Column names are  explained below.

* plot_id: Unique identifier for each plot.
* site: General location of each plot in the Central Highlands of Victoria (one of six locations).
* date: Measurement date.
* elevation: Plot elevation in meters asl.
* aspect: Aspect associated with each plot, in degrees.
* direction: Discretized aspect associated with each plot.
* slope: Slope of the plot, in percentage.
* forest_type: Main forest type associated with the adult tree population in each plot. One of CTR (cool-temperate rainforest), TOF (Tall open forest), MF (Cool-temperate mixed forest), and DSF (dry sclerophyll forest).
* fire_intensity: Mean latent relative fire intensity per plot estimated by Eq. 1.
* prop_top_kill_BA: Proportion of full_kill trees per plot in temrs of basal area.
* prop_top_kill_N: Proportion of full_kill trees per plot in temrs of tree count.
* seedling_composition: Main forest type associated with the seedling population in each plot. One of CTR (cool-temperate rainforest), TOF (Tall open forest), MF (Cool-temperate mixed forest), DSF (dry sclerophyll forest), US (understorey species), and None (no seedlings in the plot).

Cite the data:
[![DOI](https://zenodo.org/badge/362739469.svg)](https://zenodo.org/badge/latestdoi/362739469)

