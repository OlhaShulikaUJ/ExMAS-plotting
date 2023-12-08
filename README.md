# ExMAS-plotting

We conducted the experiment based on actual trip requests in New York City from 2016. The source files were uploaded here: https://zenodo.org/records/7437768. 
The whole dataset comprises half a year of consistent data (24h/day). We divided the dataset into half hour batches. Each batch constitutes a separate demand structure (set of requests). Number of requests varies from 1 up to 315.

All parameters are assumed constant during the analysis. To mention the few most important, we assume 
- the value of time to be 11.6 $/h; 
- price of 1.38 $/km; 
- willingness to share at level 1.3. 

The discount level for ride-pooling is 0.32. 

The results of applying the ExMAS algorithm [https://github.com/RafalKucharskiPK/ExMAS/tree/master/ExMAS] are presented in the file [https://github.com/OlhaShulikaUJ/ExMAS-plotting/KPI/KPI_resultsNYC.csv].

To analyse raid-hailing trip demand, it is necessary to use this file [https://github.com/OlhaShulikaUJ/ExMAS-plotting/tree/main/NYC DEMAND.ipynb].

To analyse KPIs, it is necessary to use this file [https://github.com/OlhaShulikaUJ/ExMAS-plotting/tree/mainNYC KPI DA.ipynb]. To create a figure to observe how the price (discount) affects pooling performance, you will also need a file [https://github.com/OlhaShulikaUJ/ExMAS-plotting/tree/main/df.csv] containing the results of applying the algorithm at discount levels of 0.2, 0.24, 0.28.

To plot hexagons, it is necessary to use this file [https://github.com/OlhaShulikaUJ/ExMAS-plotting/tree/mainplot_hexagons.ipynb].

Kucharski R., Shulika O., Bujak M., Ghasemi F., 2022/2023
