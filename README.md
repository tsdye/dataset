# dataset
Datasets for the R package ArchaeoPhases  

These files were moved out of the data/ folder.

The files have been updated so the 'magic number' is compatible with loading from a connection with a recent version of R.

An example of the update process:

> library(ArchaeoPhases)

> data(KAPhasesChronoModel)

> save(KAPhasesChronoModel, file = "KAPhasesChronoModel.RData")
