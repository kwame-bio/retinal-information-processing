# Getting Started with Retinal Information Processing

## Overview
This repository contains a complete computational neuroscience pipeline investigating how retinal systems encode and preserve visual information under biological noise.

## Quick Setup

### Prerequisites
- Python 3.8 or higher
- Git
- Virtual environment (recommended)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/kwame-bio/retinal-information-processing.git
   cd retinal-information-processing
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter**
   ```bash
   jupyter notebook
   ```

## Research Pipeline

Follow these notebooks in order to understand the complete research progression:

| # | Notebook | Focus |
|---|----------|-------|
| 01 | Signal Visualization | Foundational retinal waveform simulation |
| 02 | Dataset Loading | Data structures and preparation |
| 03 | Noise Modeling | Biological variability effects |
| 04 | PCA Analysis | Dimensionality reduction & pattern discovery |
| 05 | Fourier Analysis | Frequency-domain signal decomposition |
| 06 | Receptive Field Modeling | Center-surround spatial filtering |
| 07 | Spike Train Modeling | Temporal neural firing patterns |
| 08 | Signal Filtering | Noise recovery techniques |
| 09 | Real Retinal Data | Experimentally-inspired dataset analysis |
| 10 | Signal Clustering | Machine learning pattern identification |
| 11 | Convolution Processing | Biologically-inspired visual filters |
| 13 | Statistical Analysis | Characterizing neural variability |
| 14 | Information Theory | Shannon entropy & encoding efficiency |

## Key Research Questions

- **Signal Fidelity**: How do retinal systems preserve useful information under noisy biological conditions?
- **Neural Encoding**: How can spike trains and retinal activity represent visual information over time?
- **Biological Organization**: Can computational analysis reveal hidden structure in retinal neural activity?
- **Information Efficiency**: How efficiently can retinal systems encode visual information despite biological variability?

## Technologies Used

- **Python**: Core analysis language
- **NumPy & Pandas**: Numerical computing and data manipulation
- **Matplotlib & Seaborn**: Data visualization
- **Scikit-learn**: Machine learning and dimensionality reduction
- **SciPy**: Signal processing and statistical analysis

## Project Structure

```
retinal-information-processing/
├── 01_signal_visualization.ipynb
├── 02_retinal_dataset_loading.ipynb
├── 03_retinal_noise_modeling.ipynb
├── 04_pca_signal_analysis.ipynb
├── 05_fourier_signal_analysis.ipynb
├── 06_receptive_field_modeling.ipynb
├── 07_spike_train_modeling.ipynb
├── 08_signal_filtering.ipynb
├── 09_real_retinal_data_analysis.ipynb
├── 10_retinal_signal_clustering.ipynb
├── 11_convolution_visual_processing.ipynb
├── 13_statistical_signal_analysis.ipynb
├── 14_information_theory_retinal_encoding.ipynb
├── index.html
├── requirements.txt
├── GETTING_STARTED.md
├── research_summary.md
└── retinal_information_processing_paper.md
```

## Running Specific Analysis

Each notebook is self-contained and can be run independently. However, sequential execution (01 → 14) provides the optimal learning progression.

### Example: Run PCA Analysis
```python
# Open notebook 04_pca_signal_analysis.ipynb and execute all cells
# This will:
# - Generate simulated retinal signals
# - Apply principal component analysis
# - Visualize dominant modes of neural activity
# - Quantify variance explained by components
```

## Troubleshooting

**ModuleNotFoundError**: Ensure you've activated your virtual environment and run `pip install -r requirements.txt`

**Notebook won't open**: Update Jupyter: `pip install --upgrade jupyter`

**Memory issues with large datasets**: Reduce sample sizes in notebook parameters or increase system RAM

## Next Steps

1. Work through notebooks sequentially
2. Modify parameters to explore different signal regimes
3. Extend analyses with your own research questions
4. Consider applying techniques to real experimental retinal datasets

## References & Resources

- Computational Neuroscience fundamentals
- Signal Processing: Fourier & filtering theory
- Information Theory: Shannon entropy and neural coding
- Machine Learning: PCA, clustering, and pattern recognition

## Questions or Contributions?

This portfolio represents undergraduate-level computational neuroscience research. Feedback and questions are welcome!

---

**Author**: Kwame Osei  
**Institution**: Mohawk Valley Community College (transferred to Harvard)  
**Research Focus**: Retinal information processing, computational neuroscience, biological signal analysis