# ChEZ-data

"""
This repository contains datasets and related materials for research on forest ecosystems and their radioactive contamination in the Chornobyl Exclusion Zone (ChEZ).
"""

## Description
The data and ML models are provided to support:
- Forest biomass and growing stock estimation
- Analysis of radionuclide contamination (Cs-137, Sr-90) in tree wood and soils in Chornobyl forests
- Spatial analysis and mapping of ecological parameters
- Applications of ML algorithms in environmental modeling

## Repository Structure
- `ChEZ-data/Supplementary_materials_2023/` is the first dataset and models collection in the research, where:  
  `/01_biomass_processing/` is the forest parameters at the plots outside the ChEZ;  
  `/02_above_ground_measurements_for_RN/` is the forest parameters and Sr-90 / Cs-137 contents at plots in the Chornobyl Exclusion Zone;  
  `/03_est_of_biomass_&_RN_at_site_using_UAV_data/` is the main input and output results of UAV surveys on polygons;  
  `/04_classification_of_ChEZ_landscapes/` includes Jupyter notebooks with classifications of Chornobyl areas by main landscapes based on satellite data;  
  `/05_est_biomass_&_RN_Tag_use_Sentinel_data/` contains the outcomes of estimating forest stand parameters and aggregated transfer factors of Sr-90 and Cs-137 from soil to trunk wood using Sentinel-1/2 satellite images;  
  `/06_the_algorithm_to_forecast_of_the_Chornobyl_forest/` is a detailed algorithm for the evaluation of the parameters of the Chornobyl forests in the Ukrainian part of the ChEZ during 2020–2050.
- `ChEZ-data/Supplementary_materials_2024 (adapted ver)/` is the dataset with models collection of the investigations as of 2024/09/18; structure similar to `ChEZ-data/Supplementary_materials_2023/`.

## Citation
If you use these data in your research, please cite the archived version (v1.0.4) of this repository:
>Holiaka, D. (2025). ChEZ-data: Datasets of stand parameters and radionuclide content in forest components (wood and soil) with results training ML models based on them for estimating ecological and economical roles of woody ecosystems in the Chornobyl Exclusion Zone [Data set]. (All versions). https://doi.org/10.5281/zenodo.17155398

## License
The contents of this repository are released under the **MIT License** (see LICENSE file).

## Contribution
Contributions are welcome. Please create an issue or submit a pull request if you would like to add improvements, corrections, or new datasets.

## Contact
Author: Dmytrii Holiaka  
Email: golyaka.d@gmail.com
