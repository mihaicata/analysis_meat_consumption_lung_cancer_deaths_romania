# Analysis of correlation between meat consumption and number of lung cancer deaths in Romania
This experiment tries to identify whether a correlation can be established between the meat consumption per capita and the number of lung cancer deaths in Romania over a period of 28 years. The input consists of two data sets, one about cancer deaths by type and one about meat consumption per capita per category (poultry, pigmeat etc). The output consists of a newly created data set based on the processed data from the input ones and two visualizations that help us examine whether the correlation exists or not, which are interpreted.

### The data
The data was collected from openly available research data sets offered by the University of Oxford. Two data sets were used, one containing data about [worldwide meat consumption per capita](https://ourworldindata.org/grapher/per-capita-meat-consumption-by-type-kilograms-per-year?country=~OWID_WRL), and one containing data about   [worldwide deaths caused by cancer categorized by cancer type](https://ourworldindata.org/grapher/total-cancer-deaths-by-type?country=~OWID_WRL). The data was recorded yearly for each country and is split by meat type/cancer type respectively (a different column per meat type/cancer type).

### To run this experiment:
* run *requirements.txt* to install all required libraries
* open the .ipynb file from the folder *code*
* replace the location from where the two datasets are read according to the location of your files
* replace the location where the two visualisations will be saved if you don't like the default one
* enjoy!

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4685759.svg)](https://doi.org/10.5281/zenodo.4685759)
