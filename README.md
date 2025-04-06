## Singapore Trait Diversity Manuscript (SGTraitDiversity)
Analyses for coral metric trends on Singapore reefs through time.

### Please see the following paper for details.
 Chan et al. 2024 Decadal decline of functional diversity despite increasing taxonomic and phylogenetic diversity of coral reefs under chronic urbanisation stress. Ecological Indicators 164, 112143. 
 https://doi.org/10.1016/j.ecolind.2024.112143
 
 ## Data sources
 ### database
 Original data files before processing
 #### RSTBtree.tre, Genus.tre
 Species-level phylogenetic tree for all coral species, and same tree trimmed to genus level from https://doi.org/10.1098/rstb.2014.0010
 #### fulltraits.csv
 Full traits list downloaded from https://coraltraits.org/
 #### genera.t.csv, modgenera.t.csv, species.t.csv
 Genera, modern genera and species level transect data
 #### rdbspecieslist.csv
 Singapore Red Data Book species list from https://www.nparks.gov.sg/biodiversity/wildlife-in-singapore/species-list/cnidaria-(scleractinia)---stony-corals
 ### database processed
 Data files after processing for use with analyses
 #### globalspptraits.csv
 Processed trait values for all species
 #### sgspptraits.csv
 Processed trait values for all Singapore species
 #### sgspptraits_edit.csv
 Infilled sgspptraits.csv with measured trait values
 ## Codes
 ### 01_Preprocessing.qmd
 Preprocessing of data files, mainly for processing traits from the coraltraits database download
 ### 02_Processing.qmd
 Diversity calculations and compilation for modelling
 ### 03_Modelling.qmd
 Models for analyses
 ### 04_Outputs.qmd
 Figures and posteriors from models 
 ### 05_SupplementaryModels.qmd
 Supplementary models and material for supplementary file
