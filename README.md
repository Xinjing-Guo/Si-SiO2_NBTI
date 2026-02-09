# Si-SiO2 NBTI: Data and Code Repository

This repository contains the simulation pameters, simulation results, and analysis scripts used in the published article XXX.

## 📋 Overview

This project investigates NBTI reliability mechanisms in Si/SiO2 MOSFETs through first-principles calculations and reliability simulations. The repository provides all necessary data and code to reproduce the results presented in the associated research article.

## 📁 Repository Structure

```
Si-SiO2_NBTI/
├── Codes/                              # Analysis and visualization codes
│   ├── CC-Diagram/                     # Configuration Coordinate (CC) diagram generation
│   ├── DeltaVth/                       # Threshold voltage shift (ΔVth) calculations
│   ├── E_R-E_t-map/                    # Relaxation energy vs. trap energy mapping
│   └── Rate_Compare/                   # Charge capture/emission rate comparisons
│
└── Simulation_Parameters_and_OUT/      # Simulation inputs and outputs
    ├── DFT/                            # Density Functional Theory calculation data
    └── Reliability_Simulation/         # Reliability simulation parameters and results
```

## 🔬 Components Description

### Codes Directory

#### 1. **CC-Diagram**
- Generates Configuration Coordinate (CC) diagrams for charge transitions
- Visualizes energy barriers and transition paths
- Illustrates charge capture and emission processes

#### 2. **DeltaVth**
- Calculates threshold voltage shift (ΔVth) over time
- Processes experimental and simulation data

#### 3. **E_R-E_t-map**
- Creates 2D maps of relaxation energy (E_R) vs. trap energy (E_t)
- Identifies dominant defect configurations

#### 4. **Rate_Compare**
- Compares charge capture rates of V_O^0 (Si-dimer) -- V_O^+ (Si-dimer) with that of V_O^0 (Si-dimer) -- V_O^+ (Inplane)
- Field dependence analysis
- Multi-phonon transition rate calculations

### Simulation_Parameters_and_OUT Directory

#### 1. **DFT**
Contains first-principles calculation data including:
- INCAR, KPOINTS, POTCAR (Only head), OSICAR

#### 2. **Reliability_Simulation**
Contains reliability modeling data including:
- Simulation input parameters
- Time-dependent degradation data
- Output files and analysis results

## 🚀 Getting Started

### Prerequisites

The codes in this repository may require:
- Python 3.10 (for data analysis scripts)
- NumPy, SciPy, Matplotlib (Python packages)
- DFT software outputs (VASP)

### Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/[username]/Si-SiO2_NBTI.git
   cd Si-SiO2_NBTI
   ```

2. **Navigate to specific analysis**
   ```bash
   cd Codes/[analysis-type]
   ```

3. **Run analysis scripts**
   - Follow instructions in individual code directories
   - Modify parameters as needed for your analysis

## 📖 Citation

If you use this code or data in your research, please cite:

```bibtex
@article{Guo_NBTI_2024,
  title={[Article Title]},
  author={Guo, Xinjing and [Co-authors]},
  journal={[Journal Name]},
  year={2024},
  volume={[Volume]},
  pages={[Pages]},
  doi={[DOI]}
}
```

## 📄 License

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

[![CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-sa/4.0/)

**You are free to:**
- Share — copy and redistribute the material
- Adapt — remix, transform, and build upon the material

**Under the following terms:**
- **Attribution** — You must give appropriate credit
- **NonCommercial** — You may not use the material for commercial purposes
- **ShareAlike** — If you remix, transform, or build upon the material, you must distribute your contributions under the same license

## 🤝 Contributing

This is a research data repository associated with a published article. For questions or issues:
- Open an issue in the GitHub repository
- Contact the corresponding author via email

## 👥 Authors

**Xinjing Guo**
- [Fudan University]
- [xinjingguo22@m.fudan.edu.cn]


## 📝 Notes

- All data is provided as-is for research purposes
- Simulation parameters are documented in respective directories
- For detailed methodology, refer to the published article

## ⚙️ Computational Details

- **DFT Calculations**: [VASP used]
- **Exchange-Correlation Functional**: [HSE]
- **K-point Sampling**: [Gamma]
- **Convergence Criteria**: [Energy/force convergence]

## 📧 Contact

For questions about the code, data, or methodology:
- **Email**: [chensy@fuda.edu.cn]
- **GitHub Issues**: [repository issues page]

---

**Last Updated**: February 2026

**Repository Status**: Active Development / Data Release
