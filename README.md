# Flash-Separation-of-Ethanol-Water-Mixture-DWSIM-Simulation
Flash separation simulation of a 50/50 ethanol/water mixture using DWSIM. Investigated vapour-liquid equilibrium at varying temperatures using the PRSV2-VL thermodynamic model. Vapour phase enriched to 66.8% ethanol at 353K. Results highlight azeotropic limitations of single-stage separation.
This project simulates the vapour-liquid separation of an ethanol/water mixture using a flash separator in DWSIM, a professional open-source process simulation tool used in chemical engineering.
Objective

To investigate the vapour-liquid equilibrium behaviour of a 50/50 ethanol/water feed stream under varying temperature conditions, and evaluate the effectiveness of a single-stage flash separator for ethanol enrichment.
Simulation Setup

Software: DWSIM (open-source process simulator)
Thermodynamic model: Peng-Robinson-Stryjek-Vera 2 (PRSV2-VL)
Feed composition: 50% ethanol, 50% water (molar basis)
Feed flow rate: 100 mol/s
Pressure: 101,325 Pa (1 atm)
Temperatures tested: 353.15 K (80°C) and 320 K (47°C)

Key Results

At 353.15 K, the vapour outlet stream achieved an ethanol molar fraction of 66.8%, demonstrating that ethanol preferentially concentrates in the vapour phase due to its higher volatility
Sensitivity analysis across temperatures revealed limited additional enrichment, consistent with the known ethanol/water azeotrope at 95.6% ethanol
Results confirm that a single flash separator is insufficient for high-purity ethanol separation — a distillation column with multiple equilibrium stages would be required

Key Conclusions

Ethanol/water separation is limited by azeotropic behaviour, a well-known challenge in chemical engineering and industrial bioethanol production
PRSV2-VL property package accurately captures the non-ideal behaviour of polar mixtures such as ethanol/water
This simulation provides a foundation for a more advanced distillation column study

Tools Used

DWSIM | PRSV2-VL Thermodynamic Model | Vapour-Liquid Equilibrium | Flash Separation | Sensitivity Analysis
