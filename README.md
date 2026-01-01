# Predictive Maintenance Notebooks

**Hands‑on, production‑minded notebooks and examples for predictive maintenance** — feature engineering, model recipes (classical and deep), embedding‑based anomaly detection, calibration, and end‑to‑end demo pipelines. Each notebook is paired with a guided walkthrough video to speed learning and reproducibility.

---

## Overview

This repository contains curated Jupyter notebooks, small datasets, and helper scripts that demonstrate practical approaches to predictive maintenance and anomaly detection. The materials are designed for engineers and data scientists who want a runnable, explainable pipeline they can adapt to real systems.

**Highlights**
- **End‑to‑end examples** from data generation and imputation to online detection and visualization  
- **Multiple model families**: LSTM, GRU, TCN, Transformer, seq2seq autoencoders, Random Forest, Isolation Forest, One‑Class SVM, LightGBM, k‑NN density methods  
- **Detection framework** using embedding PCA residuals + empirical tail → evidence transform → CUSUM accumulator  
- **Calibration and benchmarking** utilities to choose thresholds by Monte Carlo ARL and compare detectors

---
## Video Walkthrough (recommended)

Watch the guided walkthrough before running the notebooks — it explains the pipeline, highlights the key cells to run, and shares practical tips.

Video walkthrough: https://youtu.be/jEtGY2IeDNY?si=W57RzC7MCr8kOQwd

---
## Contributing and License
Contributing

Open an issue for bugs, feature requests, or dataset suggestions.

Fork the repo, create a branch feature/your-change, and open a pull request with a clear description and example outputs.

Keep notebooks tidy: clear top‑cell instructions, minimal long outputs, and a short summary cell describing what changed.

License

This project is released under the MIT License.

---
## Quick Start

**Clone the repo**
```bash
git clone https://github.com/akzare/predictive-maintenance-notebooks.git
cd predictive-maintenance-notebooks

