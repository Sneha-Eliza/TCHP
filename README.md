# TCHP
This study explores the critical factors influencing the intensity and track of tropical cyclones in the North Indian Ocean, a region renowned for its frequent and severe cyclones, especially during the pre-monsoon and post-monsoon seasons. By examining key oceanic parameters such as Sea Surface Temperature (SST), Oceanic Heat Content (OHC), and Tropical Cyclone Heat Potential (TCHP), the research aims to enhance the accuracy of cyclone predictions. TCHP, an integrated measure of heat from the sea surface to the 26℃ isotherm, is identified as a pivotal factor in cyclone intensification, alongside SST, which influences cyclone genesis.

The study also delves into the role of air-sea interactions, particularly latent and sensible heat fluxes, in supplying energy to cyclones. It highlights seasonal variations in the impact of TCHP on cyclones in the Arabian Sea and Bay of Bengal, noting that some cyclones exhibit anomalous behavior due to short residence times or dominant atmospheric factors. By analyzing these parameters, the research provides insights into the mechanisms driving cyclone intensity changes, aiming to improve forecasting and mitigate the impacts of these destructive natural events.

# DATA USED
Latent heat flux

The data on latent heat flux is downloaded from the NCEP2 daily reanalysis. The NCEP Reanalysis 2 is based on the widely used NCEP/NCAR reanalysis. NCEP Reanalysis 2 is an improved version of the NCEP Reanalysis I model that has bug fixes and updated physical process parameterizations. It uses a state-of-the-art analysis/forecasting system to perform data assimilation using historical data from 1979 to the previous year. A large subset of this data is available from NOAA's Physical Sciences Division (PSD) in its original four times daily format and as daily averages. It includes daily data from 1979 to 2022. It provides global data with a spatial resolution of 2.5° x 2.5°.

Specific humidity

The data on specific humidity is downloaded from the NCEP reanalysis. The NCEP/NCAR Reanalysis 1 project performs data assimilation using a state-of-the-art analysis/forecast system from 1948 to the present. A large subset of this data is available from PSL in its original four times daily format and as daily averages. It has a special coverage of 2.5° x 2.5° global grids (144 x 73). The specific humidity at 2m level is used for this study.

Subsurface temperatures

The subsurface temperature from the surface to a depth of 500 m is used to compute the TCHP. The data is downloaded from Global Ocean Forecasting System (GOFS) 3.1. It consists of data from 1994 to 2022. Its grid size is 0.08° x 0.08° between 40°S-40°N. Poleward of 40°S/40°N, the grid size is 0.08° x 0.04°. It spans 80°S to 90°N. The system uses the Navy Coupled Ocean Data Assimilation (NCODA) system (Cummings, 2005; Cummings and Smedstad, 2013) for data assimilation. The data on subsurface temparature during the occurrence of  the respective cyclones is used to compute the TCHP.

SST

The data on SST is downloaded from NOAA’s 1/4-degree Daily Optimum Interpolation Sea Surface Temperature (OISST). The data is produced by interpolating and extrapolating SST observations from different sources. The data sources include the AVHRR satellite and in situ platforms like ships, buoys etc. It incorporates global data of special coverage 0.25° x 0.25°. It contains daily data from 1 September 1981 to the present day. The SST data corresponding to the dates of occurrence of the respective cyclones is used.

Computation of tropical cyclone heat potential

Tropical cyclone heat potential is an estimate of oceanic heat content. It acts as a potential indicator for genesis, intensification and propagation tracks of tropical cyclones. It is defined as the integrated heat from the sea surface to the depth of the 26°C isotherm.
 It is computed as:
 
$$
\text{TCHP} = \rho C_p \int_{0}^{D26} (T - 26) \ dz
$$

where, $\rho\$  (1026 kg m-3) is the average density of the sea water, $C_p$(4178 J kg-1 ℃-1) is the specific heat capacity of sea water at constant pressure, T is the temperature of each layer of dz thickness and D26 is the depth of the 26℃ isotherm. 

Computation of anomalies

In order to compute the latent heat flux anomaly and specific humidity anomaly, data from 1990 to 2020 is used. The daily climatology is computed from this data. The difference between the daily data and daily climatology gives the anomaly for that particular date. The daily anomaly for the period of occurrence of the cyclones is computed in this manner.
