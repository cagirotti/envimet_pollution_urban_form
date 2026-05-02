# Simulation Description

## Overview

This dataset contains ENVI-met simulation setups designed to analyze airflow patterns and pollutant dispersion within urban canyon environments.

The simulations explore the influence of urban morphology and vegetation on microclimatic conditions and air quality.

## Model Characteristics

* Simulation tool: ENVI-met
* Scale: Urban canyon
* Focus:

  * Air temperature
  * Wind flow
  * Pollutant dispersion
  * Vegetation effects

## Methodological Context

These simulations were developed as part of a broader research framework combining:

* Computational modeling (ENVI-met)
* Analysis of urban form and vegetation structure

## Reproducibility Notes

Due to ENVI-met limitations:

* `.SIMX` files store absolute file paths
* Users must manually relink `.INX` files after opening the simulation
* File paths will differ depending on the local environment

## Usage Workflow

1. Open ENVI-met
2. Load `.SIMX` file
3. Update model path to `.INX`
4. Run simulation

## Limitations

* Simulation outputs are not included
* Results depend on local execution and ENVI-met configuration
* Software is proprietary and requires a valid license
