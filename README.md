# Electrochemical Analysis Script

A Python script for automated analysis of electrochemical data from OER (Oxygen Evolution Reaction) experiments.

## What it does
- Automatically loads LSV and CA data from Excel files
- Cleans and normalizes data (converts to RHE scale and mA/cm²)
- Plots LSV curves, Tafel plots and Chronoamperometry (CA) curves
- Extracts key metrics: onset potential, overpotential and Tafel slope
- Generates a publication quality report as PNG and PDF

## Requirements
- Python (Miniconda/Anaconda)
- pandas, numpy, matplotlib, scipy, openpyxl

## How to use
1. Put your LSV files in `input_data/LSV_data/`
2. Put your CA files in `input_data/CA_data/`
3. Update electrode area and pH in Cell 6
4. Run all cells

## Experimental conditions
- Electrolyte: 1M KOH
- Reference electrode: Hg/HgO
- Electrode area: 0.25 cm²
