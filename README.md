

Klipp2002_MetabolicOptimization_linearPathway(n=2)

The model describes time dependent gene expression as a means to enable cells
to adapt metabolic activity optimally based on environmental conditions. It
uses a simple unbranched pathway and a constraint of fixed total enzyme. It
calculates enzyme profiles at different times which optimise a performance
function, and compares them to experimental data. The initial model is cell-
type agnostic, while the experimeental data is from yeast.

This model is described in the article:

[Prediction of temporal gene expression. Metabolic opimization by re-
distribution of enzyme activities.](http://identifiers.org/pubmed/12423338)

Klipp E, Heinrich R, Holzhütter HG.

Eur. J. Biochem. 2002 Nov; 269(22): 5406-5413

Abstract:

A computational approach is used to analyse temporal gene expression in the
context of metabolic regulation. It is based on the assumption that cells
developed optimal adaptation strategies to changing environmental conditions.
Time- dependent enzyme profiles are calculated which optimize the function of
a metabolic pathway under the constraint of limited total enzyme amount. For
linear model pathways it is shown that wave-like enzyme profiles are optimal
for a rapid substrate turnover. For the central metabolism of yeast cells
enzyme profiles are calculated which ensure long-term homeostasis of key
metabolites under conditions of a diauxic shift. These enzyme profiles are in
close correlation with observed gene expression data. Our results demonstrate
that optimality principles help to rationalize observed gene expression
profiles.

This model is from the paper _Prediction of temporal gene expression metabolic
optimization by re-distribution of enzyme activities._ The model describes
optimal enzyme profiles and metabolite time courses for a simple linear
metabolic pathway (n=2). Figure 1 was reproduced using roadRunner. The values
of k1 and k2 were not explicitly stated in the publication, but calculations
were performed for equal catalytic efficiencies of the enzymes (ki=k), hence
the curator assigned k1=k2=1. Also enzyme concentrations are given in units of
Etot; times are given in units of 1/(k*Etot) in the papaer, for simplicity ,
we use defalut units of the SBML to present the concentration and time.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[MODEL4931762955](http://identifiers.org/biomodels.db/BIOMD0000000104) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

