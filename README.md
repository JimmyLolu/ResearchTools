# AlphaPorous
### Acoustic Absorption Predictor

A free, open-source, browser-based tool for predicting sound absorption coefficients of porous materials.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18675581.svg)](https://doi.org/10.5281/zenodo.18675581)

## 🌐 Live Tool

**Access AlphaPorous online:** [alphaporous.com](https://alphaporous.com)

No installation required - runs entirely in your browser!

---

## 📖 About

AlphaPorous implements seven established acoustic models for predicting how porous materials absorb sound. Designed for researchers, engineers, and students working with acoustic materials.

**Key Features:**
- 🔬 **7 Acoustic Models** - Delany-Bazley, Miki, JCA, JCAL, Biot, Zwikker-Kosten, TMM
- 📊 **Real-time Plotting** - Interactive frequency-domain visualization
- 🔢 **NRC Calculation** - Automatic Noise Reduction Coefficient
- 📈 **Multi-curve Comparison** - Overlay up to 10 configurations
- 💾 **CSV Export** - Download data for further analysis
- 🌐 **No Installation** - Runs entirely client-side in browser
- 🔓 **Open Source** - MIT License

---

## 🚀 Quick Start

1. **Visit:** [alphaporous.com](https://alphaporous.com)
2. **Select a model** from the sidebar
3. **Enter material parameters**
4. **Click "Add to Chart"**
5. **Analyze the absorption curve**

**[📘 Download User Guide (PDF)](https://alphaporous.com/docs/AlphaPorous_UserGuide_v1.pdf)**

---

## 🔬 Implemented Models

### Empirical Models
- **Delany-Bazley (1970)** - Classic model for fibrous materials
- **Miki (1990)** - Improved low-frequency accuracy

### Semi-Empirical Models
- **Johnson-Champoux-Allard (JCA)** - Viscous + thermal dissipation
- **JCAL (Lafarge, 1997)** - Extended JCA with thermal permeability
- **Biot (1956)** - Includes frame elasticity effects

### Phenomenological Models
- **Zwikker-Kosten** - Capillary tube model
- **Transfer Matrix Method (TMM)** - For layered systems

---

## 🎯 Use Cases

- **Building Acoustics** - Design sound-absorbing panels
- **Automotive NVH** - Optimize cabin acoustic treatments
- **Materials Research** - Validate experimental measurements
- **Education** - Teach acoustic material behavior
- **Product Development** - Compare material configurations

---

## 💻 Local Usage

**Option 1: Use Online** (Recommended)
- Visit [alphaporous.com](https://alphaporous.com)

**Option 2: Download and Run Locally**
```bash
# Clone repository
git clone https://github.com/JimmyLolu/acoustic-absorption-predictor.git

# Open in browser
cd acoustic-absorption-predictor
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

No build process or dependencies required!

---

## 📖 Documentation

**[User Guide (PDF)](https://alphaporous.com/docs/AlphaPorous_UserGuide_v1.pdf)** - Comprehensive guide including:
- Model descriptions and equations
- Parameter explanations
- Step-by-step workflows
- Troubleshooting
- Citation formats

---

## 📊 Citation

If you use AlphaPorous in your research, please cite:

**APA:**
```
Olajide, J. L. (2026). AlphaPorous: A browser-based tool for acoustic 
absorption prediction (Version 1.0.0) [Software]. Zenodo. 
https://doi.org/10.5281/zenodo.18675581
```

**BibTeX:**
```bibtex
@software{olajide2026alphaporous,
  author       = {Olajide, Jimmy Lolu},
  title        = {AlphaPorous: A Browser-Based Tool for 
                  Acoustic Absorption Prediction},
  year         = {2026},
  publisher    = {Zenodo},
  version      = {1.0.0},
  doi          = {10.5281/zenodo.18675581},
  url          = {https://doi.org/10.5281/zenodo.18675581}
}
```

---

## 🤝 Contributing

Contributions are welcome! Please feel free to:
- Report bugs via [Issues](https://github.com/JimmyLolu/acoustic-absorption-predictor/issues)
- Suggest new features
- Submit pull requests
- Improve documentation

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

You are free to:
- ✅ Use commercially
- ✅ Modify
- ✅ Distribute
- ✅ Use privately

---

## 🙏 Acknowledgments

Developed as part of postgraduate research at:

**University of South Africa (UNISA)**  
Department of Mechanical, Bioresources and Biomedical Engineering

Research focus: Sustainable acoustic composites from waste materials within a circular economy framework.

---

## 📬 Contact

**Jimmy Lolu Olajide**  
Postgraduate Researcher  
University of South Africa (UNISA)

- 🌐 [alphaporous.com](https://alphaporous.com)
- 📧 [ResearchGate](https://www.researchgate.net/profile/Jimmy-Olajide)
- 🎓 [Google Scholar](https://scholar.google.com/citations?user=HulJMpkAAAAJ)

---

## 🔗 Related Resources

- [User Guide](https://alphaporous.com/docs/AlphaPorous_UserGuide_v1.pdf) - Full documentation
- [Live Tool](https://alphaporous.com) - Browser-based application
- [Zenodo Archive](https://doi.org/10.5281/zenodo.18675581) - Permanent DOI

---

**Built with vanilla JavaScript | No frameworks | No dependencies**

© 2026 Jimmy Lolu Olajide | MIT License
