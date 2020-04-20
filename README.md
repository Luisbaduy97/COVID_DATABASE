# COVID_DATABASE
This repository shows how to develop a database with information on COVID-19 and different environmental, economic and social factors of the different countries that are affected by the pandemic.
<p align="center"><img src="https://www.hoyesarte.com/wp-content/uploads/2020/03/covid-19.jpg" width="800" height="300"></p>

In this repository you will find different jupyter notebooks codes:
1. Ambientales.ipynb allows to acquire the temperature of countries with covid, such as:
   * Temperature
   * Feels like temperature
   * Min temperature
   * Max temperature
   * Pressure
   * Humidity
2. Buscando_en_data_basic.ipynb allows to create a new dataset with features like:
   * Population
   * Urban Population
   * Density
   * Median age
   * Migrants
3. Completando_datasets.ipynb allows to fill the datasets previously downloaded from https://ourworldindata.org/ with information about:
   * New cases from December 31, 2019 until April 19, 2020
   * New deaths from December 31, 2019 until April 19, 2020
   * Total cases from December 31, 2019 until April 19, 2020
   * Total deaths from December 31, 2019 until April 19, 2020
4. Unión_datos.ipynb: allow to create a dataset with information about temperature previously acquired Ambientales.ipynb and with the following features:
   * GDP per capita from 2018
   * CHE per capita from 2017
   This datasets were downloaded from https://apps.who.int/gho/data/node.home
5. Final.ipynb allows to create a new dataset with all the features previously acquired from all the different notebooks
Datasets with all the information with tab separator is COVID_DATASET.csv and COVID_DATASET_COMMAS.csv with comma separator 
