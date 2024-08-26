# lifetables4archeologists

The dataset contains mortality data of humans taken from the literature. Therefore, the data is heterogeneous in many respects, especially with regard to the quality of the anthropological information. However, the data is simplified and classified to fit into a limited number of columns, e.g. a general archaeological classification. The dataset is designed for easy use with the [R package mortAAR](https://CRAN.R-project.org/package=mortAAR) to calculate life tables in an archaeological context. 

Each data set consists of the following files: database (sqlite), literature (bibtex), documentation (Rmd, pdf). The initial data set is Germany (de_) for the Neolithic (_neol). A data set for the German Iron Age is in preparation. 

The data is provided as a sqlite database in a very simple form, not normalised or with implemented relations. The documentation (pdf) gives a first overview of the data in the database and at the same time, a simple workflow for data processing in R with the [R package mortAAR](https://CRAN.R-project.org/package=mortAAR).

A previous release of the data collection is available via [Zenodo  DOI 10.5281/zenodo.10778019 ](https://zenodo.org/records/10778019) and [LandMan](https://landman.sfb1266.uni-kiel.de/) of CRC 1266 "Scales of Transformation - Human-Environmental Interaction in Prehistoric and Archaic Societies." Deutsche Forschungsgemeinschaft (DFG) - project number 290391021
[https://gepris.dfg.de/gepris/projekt/290391021](https://gepris.dfg.de/gepris/projekt/290391021)]. Subproject: "Regional and Local Patterns of 3<sup>rd</sup> Millennium Transformations of Social and Economic Practices in the Central German Mountain Range (D2)"  [https://gepris.dfg.de/gepris/projekt/316739879](https://gepris.dfg.de/gepris/projekt/316739879)]. In addition, I have decided to set up this Github repository to make updates traceable and further additions to the database more easily accessible. 

Please acknowledge my work if you found it useful for your publications.