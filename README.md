This repository contains the files used to run the analyses associated with the paper.


RUNNING ANALYSES FOLDER (listed alphabetically)
avg_tree_manual_mean-1000.nex
Time-calibrated phylogeny for the sample of 167 living and fossil euarchontoglires.

Creating-simulation-batches.R
R code used to create simulated shape data under a Brownian Motion (BM) evolutionary model using the same tree. The simulated datasets were used as null models against which evolutionary model results were validated.

EG-Fossil-Stats.R
R code used for all analyses and figure generation.

EG-GMM-Fossil-Classifier.csv
Classifier file containing clade information used for statistical tests and figure creation.

EG_Landmarks_Good/
Folder containing the landmark coordinate files for all specimens.

Paraxerus-cepapi.ply
Surface file of Paraxerus cepapi, representing the species with the average endocranial shape. This model was used to warp the surface to the extremes of the principal component (PC) axes.

Spnames.csv
Alphabetized list of species names (in the same order as in the “EG_Landmarks_Good” folder). Used to overwrite species names and remove the “_Landmarks.landmarkAscii” suffix.


CREATING A TIME-CALIBRATED TREE FOLDER (listed alphabetically)
EG-Fossil-Treemaking.R
R code used to create the time-calibrated phylogenetic tree.

int_times-5interval.csv
File containing the ages for each time bin (in 5-million-year intervals).

Node-Legend.csv
File listing node ages obtained from a maximum clade credibility (MCC) tree for extant species, derived from a posterior distribution of trees downloaded from vertlife.org.

taxon_times-5interval.csv
File designating each taxon’s time bin assignment.

tree-mes.nex
Final time-calibrated tree used for evolutionary analyses.
