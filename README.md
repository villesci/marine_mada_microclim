# Microclimates of a Coastal Reef Zone in Southwestern Madagascar

Code repository for our preprint characterizing microclimates of coastal reef zones in Madagascar.

## Contents

-   `data/`: Raw and processed data files.
    -   `logger_data/`: temperature logger data from five sites at Salary reef.
        -   `saleb1.csv` : Shallow lagoon temperature
        -   `saleb3.csv` : Backreef temperature
        -   `saleb5.csv` : Deep lagoon temperature
        -   `saleb8.csv` : Reef flat temperature
        -   `saleb10.csv` : Air temperature Chez Fred
    -   `cop_sst.nc`: NC file of Copernicus SST data at Salary reef.
    -   `fishing_coords.csv`: CSV file containing coordinate information of named fishing sites near Salary reef
    -   `towns.csv`: CSV file containing names and coordinates of towns near Salary
    -   `site_data.csv`: CSV file containing coordinates and deployment information for temperature loggers on Salary reef
-   `scripts/`: R scripts for data processing and analysis.
    -   `salary_reeftemp.Rmd`: Main analysis script of water temperature data and modeled tide data
    -   `mada_TMD.ipynb`: Python notebook for downloading and processing tide data from the Tide Model Driver (TMD) for Salary reef.
        -   We do not include the TPX09 atlas .nc files needed to recreate the tidal analysis due to licensing. This can be obtained from <https://www.tpxo.net/tpxo-products-and-registration> ([Egbert,Gary D., and Svetlana Y. Erofeeva. "Efficient inverse modeling of barotropic ocean tides." Journal of Atmospheric and Oceanic Technology 19.2 (2002): 183-204.](https://doi.org/10.1175/1520-0426%282002%29019%3C0183:EIMOBO%3E2.0.CO;2))
    -   `python_requirements.txt`: Python requirements to run tide code
    -   `python_environment.yaml`: YAML of Jupyter notebook environment
-   `references.bib`: References used in Rmd script
