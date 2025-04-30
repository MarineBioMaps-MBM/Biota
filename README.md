# Biotic Components Analysis

## Author: Madison Enda 

### Contributors: Bailey Jorgensen, Michelle Yiv, Cori Lopazanski, Samantha Stevenson-Karl

The Pacific Marine and Estuarine Partnership (PMEP) utilized the Coastal & Marine Ecological Classification Standard (CMECS) to define major biotic categories:

- **Aquatic Vegetation Bed:** This class includes subtidal or intertidal bottoms and any other areas characterized by a dominant
cover of rooted vascular plants.

- **Benthic/Attached Biota:** This biotic setting describes areas where biota lives on, in, or in close association with the seafloor or
other substrates (e.g., pilings, buoys), extending down to include the layers of sediment that contain multi-cellular
life.

- **Benthic Macroalgae:** Aquatic beds dominated by other macroalgae attached to the substrate, excluding kelp.

- **Canopy-Forming Algal Bed (Kelp):** Areas dominated by canopy-forming algae that have complex growth forms with holdfasts and well-
defined stipes and blades.

- **Emergent Wetland:** Areas in this class are characterized by erect, rooted, herbaceous hydrophytes—excluding emergent
mosses and lichens.

- **Faunal Bed:** Seabeds dominated or characterized by a cover of animals that are closely associated with the
bottom, including attached, clinging, sessile, infaunal, burrowing, laying, interstitial, and slow moving animals, but
not animals that have created substrate (Reef Biota).

- **Floating/Suspended Plants and Macroalgae:** This class includes areas dominated by vascular plants, detached plant parts, or macroalgae that are
floating on the surface or are suspended in the water column—that is, plants and macroalgae that are not rooted
or attached to the bottom.

- **Forested Wetland:** Areas in this class are characterized by woody vegetation that is generally 6 meters or taller.

- **Scrub-Shrub Wetland:** Emergent wetland areas dominated by woody vegetation that is generally less than 6 meters tall.

- **Seagrass Bed:** Tidal aquatic vegetation beds dominated by any number of seagrass or eelgrass species, including
Cymocedea sp., Halodule sp., Thalassia sp., Halophilla sp., Vallisnera sp., Ruppia sp., Phyllospadix sp., and
Zostera sp..


### Data:

.rds files created in the rds_creation repository from this MarineBioMaps Github Organization were used to load in the PMEP data filtered to California. See those repositories to access these .rds files. 

Shapefiles for CA MPA Boundaries were downloaded from the [California Department of Fish and Wildlife](https://data.ca.gov/dataset/california-marine-protected-areas-ds582).

## File Contents

The Quarto Markdown files in this repository house the various analysis run to answer questions about MPA habitat components on a statewide, regional, or MPA specific level. The .qmd files are named for the respective areas being analyzed. 


### Repository Structure:
```
biota
│  └──README.md
|  └──bioregion_analysis
|     └──nccsr_substrate.qmd
|     └──scsr_substrate.qmd
|     └──ncsr_substrate.qmd
|     └──ccsr_substrate.qmd
│  └──pointlobos_substrate_analysis
|  └──statewide_substrate_analysis
|  └──saving_substrate_data
```
