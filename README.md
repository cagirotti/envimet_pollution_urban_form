# ENVI-met Urban Canyon – Air Pollution Dispersion

This repository contains ENVI-met input files used to simulate microclimate conditions and atmospheric pollutant dispersion in urban canyon environments.

## Academic Context

This simulation setup is part of the PhD research of Carolina Girotti:

"Análise da morfologia urbana e da vegetação nos Eixos de Estruturação e Transformação Urbana do município de São Paulo: Aspectos da concentração e dispersão de poluentes atmosféricos"

Faculty of Architecture and Urbanism and Design (FAU-USP)
University of São Paulo (USP)

Part of this work was published in:

Girotti, C. et al. (2026)
*Urban morphology and air quality: microclimatic simulation of PM2.5 and NO₂ dispersion in urban canyons scale*
Air Quality Atmosphere & Health , 19, 2
 https://doi.org/10.1007/s11869-026-01884-y

## Repository Structure

* `models/` → ENVI-met model files (.INX)
* `simulations/` → simulation setup files (.SIMX)
* `docs/` → additional documentation

## How to use

Due to ENVI-met file structure, simulation files require manual linking:

1. Open ENVI-met
2. Create or select a project workspace
3. Load a `.SIMX` file
4. Manually update the path to the corresponding `.INX` file on your local machine

⚠️ The `.SIMX` files contain absolute paths that must be adjusted for each user.

## Notes

* Only input files are provided
* Simulation outputs are not included due to file size constraints
* ENVI-met license is required to run simulations




