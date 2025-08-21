# CASA_TfL_Projects
# Differentiated Gentrification Pathways: NLE and BRE

<div align="center">

![TfL Logo](images/tfl_logo.png) &nbsp;&nbsp;&nbsp;&nbsp; ![CASA Logo](images/casa_logo.jpg)

</div>

---

## 📖 Abstract

This research examines TOD-induced gentrification impacts of London's **Northern Line Extension (NLE)** and **Barking Riverside Extension (BRE)** using **spatial difference-in-differences analysis** of 39 LSOAs from 2011 to 2022. The study investigates whether transit-oriented development uniformly triggers gentrification or produces differentiated outcomes across socioeconomic contexts.

### 🔑 Key Findings

- **NLE Areas**: Gradual early-stage gentrification with moderate income growth (£1,400-1,900 annually) and positive spatial spillover effects
- **BRE Areas**: Incumbent upgrading patterns with substantial income growth (£3,600-5,600) yet paradoxical housing price declines (-£21,182)
- **Spatial Effects**: Different pathways reflecting distinct urban contexts and development mechanisms

---

## 📁 Repository Structure

```
📦 Differentiated-Gentrification-Pathways-NLE-and-BRE-
├── 📂 Analysis/
│   ├── 📂 Gentrification_output/          # Main analysis results
│   ├── 📂 Index/                          # Gentrification index calculations
│   ├── 📄 LSOAs indicators/               # LSOA analysis workspace
│   ├── 📂 Parallel_test/                  # Pre-treatment trend analysis
│   ├── 📂 PSM/                           # Propensity Score Matching
│   ├── 📄 lsoa_income_estimates.csv       # SAE results
│   └── 📂 Rcode/                         # All R analysis scripts
├── 📂 Data/
│   ├── 📂 housing price/                  # Property market data
│   ├── 📂 imd/                           # Index of Multiple Deprivation
│   ├── 📂 income/                        # Income data (MSOA level)
│   ├── 📂 lookup_file/                   # Geographic lookup tables
│   └── 📂 remains/                       # Additional datasets
├── 📂 QGIS/
│   ├── 📂 Other/                         # Spatial analysis files
│   ├── 📂 PTAL/                          # Public Transport Accessibility
│   ├── 📂 PTAL_backup/                   # PTAL backup data
│   ├── 📂 Station/                       # Station location data
│   └── 📂 Treatment/                     # Treatment area definitions
└── 📂 Tables_figures/                     # Research outputs
```

---

## 🚇 Study Areas

<div align="center">

| **Northern Line Extension (NLE)** | **Barking Riverside Extension (BRE)** |
|:----------------------------------:|:--------------------------------------:|
| Nine Elms Station | Barking Riverside Station |
| Central London Location | East London Periphery |
| 35 Treatment LSOAs | 4 Treatment LSOAs |
| High Baseline Income (£50,000+) | Lower Baseline Income (£40,000) |

</div>

### Key Scripts
- `Gentrification Model.Rmd`: Comprehensive analysis workflow
- `Gentrification Measurement.Rmd`: Control group selection and validation
- `Indicators analysis.Rmd`: Data processing and SAE implementation
- `Result output.Rmd`: Final results and visualization

---

## 🎯 Policy Implications

### For Central Metropolitan Projects (NLE-type)
- Implement **social mixing strategies**
- Monitor gradual displacement risks
- Establish **affordable housing quotas**
- Create **community benefit mechanisms**

### For Peripheral Development Projects (BRE-type)
- Protect **incumbent resident rights**
- Ensure **local employment opportunities**
- Maintain **affordable housing supply**
- Establish **development benefit sharing**

## 🔗 Links & Resources

- **Analysis Results**: [Tables_figures/](./Tables_figures/)
- **TfL Official Data**: [Transport for London](https://tfl.gov.uk)
- **UCL CASA**: [Centre for Advanced Spatial Analysis](https://www.ucl.ac.uk/bartlett/casa/)

---

<div align="center">

**🚇 Transit-Oriented Development • 🏘️ Urban Gentrification • 📊 Spatial Econometrics**

*Advancing evidence-based urban policy through rigorous spatial analysis*

</div>
