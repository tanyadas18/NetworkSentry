
# NetworkSentry
### Network Threat Detection & Investigation Platform

NetworkSentry is an offline-first cybersecurity analytics project that combines data engineering, machine learning, deep learning, and interactive visualisation to analyse network traffic and support threat investigation.

## Project Objectives

- Build a repeatable pipeline for network-flow data ingestion and validation.
- Identify suspicious traffic using supervised and unsupervised learning.
- Develop a deep-learning autoencoder for anomaly scoring.
- Group related suspicious flows into investigations.
- Present traffic patterns, alerts, and data-quality metrics in an interactive dashboard.

## Planned Technology Stack

- **Language:** Python 3.12
- **Data processing:** Pandas, PyArrow
- **Analytical storage:** Parquet, DuckDB
- **Machine learning:** scikit-learn
- **Deep learning:** PyTorch
- **Testing and validation:** pytest, Pandera
- **Dashboard:** Streamlit, Plotly

## Project Status

**Phase 1 — Foundation setup**

- [x] Local project and GitHub repository created
- [x] Python virtual environment configured
- [x] Initial dependencies installed
- [ ] Dataset selected and documented
- [ ] Data-quality pipeline implemented
- [ ] Models trained and evaluated
- [ ] Investigation workflow implemented
- [ ] Interactive dashboard completed

## Data Source

The intended primary benchmark is CIC-IDS2017, published by the Canadian Institute for Cybersecurity at the University of New Brunswick.

Official source: https://www.unb.ca/cic/datasets/ids-2017.html

The exact dataset files, version, and cleaning decisions will be documented before modelling begins.

## Important Limitations

NetworkSentry is a portfolio and research project, not a production intrusion-detection system. An anomaly score is an indicator for investigation, not proof of malicious activity. Benchmark performance may not generalise to live networks.

## Reproducibility

Project dependencies are recorded in `requirements.txt`. Dataset files and local environment artefacts are excluded from version control.
