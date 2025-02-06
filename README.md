# weather-aqMilan
Python Notebooks illustrating the process for the creation of a envronmental factors dataset for the city of Milan

In the context of the Master's Degree course in Data Science at Università degli Studi di Milano-Bicocca, as a Daa Management exam course project, me and my constructed a comprehensive dataset containing information on pollutant levels and weather/atmospheric factors, in order to facilitate analysis of recent trends and hopefully extract insights into how to improve the current, unsatisfactory situation.

### Methodology
  Starting from two data sources, we collected and verified both data provenance and quality for the obtained data; which concerns the city of Milan in between the start of 2020 and end of 2023.
  The creation of the final dataset(which you can get a closer look at here:https://www.kaggle.com/datasets/edmos07/milan-air-quality-and-weather-dataset-daily/data), was achieved through Jupyter notebooks, in order     to   make our process more fragmented and clearer. 

### Special thanks
  This work was greatly enabled by Open-Meteo APIs (https://open-meteo.com/en/docs/historical-weather-api and https://open-meteo.com/en/docs/air-quality-api), which was in turn enabled by the Reanalyses models used to   provide the values in the data (CAMS European Reanalyses dataset, ERA5 and ERA5-Land, and the ECMWF IFS), my tea and I would therefore like to thank the data providers for their work and their open data policy.


#### References

METEO FRANCE, Institut national de l'environnement industriel et des risques (Ineris), Aarhus University, Norwegian Meteorological Institute (MET Norway), Jülich Institut für Energie- und Klimaforschung (IEK), Institute of Environmental Protection – National Research Institute (IEP-NRI), Koninklijk Nederlands Meteorologisch Instituut (KNMI), Nederlandse Organisatie voor toegepast-natuurwetenschappelijk onderzoek (TNO), Swedish Meteorological and Hydrological Institute (SMHI), Finnish Meteorological Institute (FMI), Italian National Agency for New Technologies, Energy and Sustainable Economic Development (ENEA) and Barcelona Supercomputing Center (BSC) (2022): CAMS European air quality forecasts, ENSEMBLE data. Copernicus Atmosphere Monitoring Service (CAMS) Atmosphere Data Store (ADS).  (Accessed on <04-FEB-2025>), https://ads.atmosphere.copernicus.eu/datasets/cams-europe-air-quality-forecasts?tab=overview

METEO FRANCE, Institut national de l'environnement industriel et des risques (Ineris), Aarhus University, Norwegian Meteorological Institute (MET Norway), Jülich Institut für Energie- und Klimaforschung (IEK), Institute of Environmental Protection – National Research Institute (IEP-NRI), Koninklijk Nederlands Meteorologisch Instituut (KNMI), Nederlandse Organisatie voor toegepast-natuurwetenschappelijk onderzoek (TNO), Swedish Meteorological and Hydrological Institute (SMHI) and Finnish Meteorological Institute (FMI) (2020): CAMS European air quality forecasts, ENSEMBLE data. Copernicus Atmosphere Monitoring Service (CAMS) Atmosphere Data Store (ADS).  (Accessed on <04-FEB-2025>), https://ads.atmosphere.copernicus.eu/datasets/cams-europe-air-quality-forecasts?tab=overview

Zippenfenig, P. (2023). Open-Meteo.com Weather API [Computer software]. Zenodo. https://doi.org/10.5281/ZENODO.7970649

Hersbach, H., Bell, B., Berrisford, P., Biavati, G., Horányi, A., Muñoz Sabater, J., Nicolas, J., Peubey, C., Radu, R., Rozum, I., Schepers, D., Simmons, A., Soci, C., Dee, D., Thépaut, J-N. (2023). ERA5 hourly data on single levels from 1940 to present [Data set]. ECMWF. https://doi.org/10.24381/cds.adbb2d47

Muñoz Sabater, J. (2019). ERA5-Land hourly data from 2001 to present [Data set]. ECMWF. https://doi.org/10.24381/CDS.E2161BAC

Schimanke S., Ridal M., Le Moigne P., Berggren L., Undén P., Randriamampianina R., Andrea U., Bazile E., Bertelsen A., Brousseau P., Dahlgren P., Edvinsson L., El Said A., Glinton M., Hopsch S., Isaksson L., Mladek R., Olsson E., Verrelle A., Wang Z.Q. (2021). CERRA sub-daily regional reanalysis data for Europe on single levels from 1984 to present [Data set]. ECMWF. https://doi.org/10.24381/CDS.622A565A
