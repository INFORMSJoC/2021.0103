[![INFORMS Journal on Computing Logo](https://INFORMSJoC.github.io/logos/INFORMS_Journal_on_Computing_Header.jpg)](https://pubsonline.informs.org/journal/ijoc)

This archive is distributed in association with the [INFORMS Journal on Computing](https://pubsonline.informs.org/journal/ijoc) under the [CC BY License](LICENSE).

This repository contains supporting material for the paper [A Multiobjective Approach for Sector Duration Optimization in Stereotactic Radiosurgery Treatment Planning](https://doi.org/????) by O. Şeker and M. Cevik and M. Bodur and Y. Lee and M. Ruschin.


## Cite

To cite this data, please cite the [research article](https://doi.org/10.1287/????) and the data itself, using the following DOI.

[![DOI](https://zenodo.org/badge/524492449.svg)](https://zenodo.org/badge/latestdoi/524492449)


Below is the BibTex for citing the data.

```
@article{Data_SDO,
author =        {O. Şeker and M. Cevik and M. Bodur and Y. Lee and M. Ruschin},
publisher =     {INFORMS Journal on Computing},
title =         {Data for Sector Duration Optimization in Stereotactic Radiosurgery Treatment Planning},
year =          {2022},
doi =           {10.5281/zenodo.7048848},
url =           {https://github.com/INFORMSJoC/2021.0103},
}  
```

## Content

This repository includes

1. A synthetic problem instance for sector duration optimization (actual patient data used in the paper is not shared due to privacy concerns)
1. A file describing instance data format  
1. A file containing sample results for the provided instance


### Data files

Instance data files are located in the folder [data](data). The folder contains five text files.

* There are four different text files containing dose rate matrices for different structures, which are one tumor & ring, and two organs-at-risk (OARs) (dose rate data are generated using two predetermined isocenter locations).
    1. Dose rate file for the tumor: [doseRateMatrix_tumor.txt](data/doseRateMatrix_tumor.txt)
    1. Dose rate file for the ring: [doseRateMatrix_ring.txt](data/doseRateMatrix_ring.txt)
    1. Dose rate file for OAR1: [doseRateMatrix_OAR1.txt](data/doseRateMatrix_OAR1.txt)
    1. Dose rate file for OAR2: [doseRateMatrix_OAR2.txt](data/doseRateMatrix_OAR2.txt) 

* There is one additional text file containing prescribed and maximum doses for each structure: [prescribedAndMaxDoses.txt](data/prescribedAndMaxDoses.txt)

### Data format
The folder [docs](docs) contains a text file [dataFormat.txt](docs/dataFormat.txt) that describes the format of the instance data files.

### Results
The file [sampleResults.txt](results/sampleResults.txt) in the folder [results](results) contains sample results for the problem instance provided in this repository, both from the weighted-objective SDO model by [Cevik et al. (2019)](https://doi.org/10.1088/1361-6560/aaf7ce) and from our multiobjective model.


