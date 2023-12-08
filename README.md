# ExMAS-plotting

We conducted the experiment based on actual trip requests in New York City from 2016. The source files were uploaded here: https://zenodo.org/records/7437768. 
The whole dataset comprises half a year of consistent data (24h/day). We divided the dataset into half hour batches. Each batch constitutes a separate demand structure (set of requests). Number of requests varies from 1 up to 315.

All parameters are assumed constant during the analysis. To mention the few most important, we assume 
- the value of time to be 11.6 $/h; 
- price of 1.38 $/km; 
- willingness to share at level 1.3. 

The discount level for ride-pooling is 0.32. 

The results of applying the ExMAS algorithm [https://github.com/RafalKucharskiPK/ExMAS/tree/master/ExMAS] are presented in the file [KPI_resultsNYC.csv] (https://github.com/OlhaShulikaUJ/ExMAS-plotting/KPI/).

To analyse raid-hailing trip demand, it is necessary to use this file [NYC DEMAND.ipynb] (https://github.com/OlhaShulikaUJ/ExMAS-plotting/tree/main).

To analyse KPIs, it is necessary to use this file [NYC KPI DA.ipynb] (https://github.com/OlhaShulikaUJ/ExMAS-plotting/tree/main).

To plot hexagons, it is necessary to use this file [plot_hexagons.ipynb] (https://github.com/OlhaShulikaUJ/ExMAS-plotting/tree/main).

Kucharski R., Shulika O., Bujak M., Ghasemi F., 2022/2023
