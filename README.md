# MultiScaleMultiFloorBuildingEvacuationSimulationAndOptimization
  
## Overview

This project presents a multi-scale simulation and optimization framework for smart evacuation in multi-floor buildings, integrating both microscopic and mesoscopic crowd dynamics models. The research addresses evacuation under normal, fire, and earthquake scenarios, aiming to improve safety and efficiency through data-driven optimization.

### Key Components
- **Microscopic Model:** Uses the Social Force Model to simulate individual pedestrian behavior and interactions.
- **Mesoscopic Model:** Aggregates groups of agents for scalable simulation of large crowds.
- **Optimization:** Employs algorithms to optimize building layouts and evacuation strategies, minimizing evacuation time and maximizing evacuation rate.

## How to Use

1. Open and run the notebook: `Script/MicroscopicMesoscopic - SOTA - Final.ipynb`.
2. Follow the notebook steps to:
   - Load building layouts and scenario parameters.
   - Simulate evacuation for different scenarios.
   - Visualize and compare results (see `Animations/` and `Figures/`).
   - Apply optimization and analyze improvements.

## Results & Visualizations

- Animated simulations and comparative figures are available in the `Animations/` and `Figures/` folders.
- Quantitative results and optimization histories are provided for each scenario.
- Data files (`.pkl`) store simulation and optimization outputs for further analysis.

## Research Highlights (from the Paper)

- Presents a unified framework for multi-scale evacuation modeling.
- Demonstrates the impact of optimization on evacuation time and rate.
- Provides scenario-based analysis for normal, fire, and earthquake conditions.
- Validates models using real building layouts and literature benchmarks.

For full details, see the paper: `Paper/Smart_Evacuation_of_Multi_Floor_Building_And_Optimization.pdf`.

## References

Key literature includes:
- Helbing (2000) – Social Force Model
- Kirchner (2002) – Cell Based Discretization
- Treuille (2010) – Continuum Crowds
- Kuligowski (2010) – Building Evacuation Models Review

See the `References/` folder for more.

## Citation

If you use this work, please cite:
`Smart_Evacuation_of_Multi_Floor_Building_And_Optimization.pdf` (see `Paper/` folder).
