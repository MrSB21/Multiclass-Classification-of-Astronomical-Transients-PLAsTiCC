# Multiclass-Classification-of-Astronomical-Transients-PLAsTiCC

I worked on classifying astronomical transients from the PLAsTiCC dataset, a benchmark designed for the Vera C. Rubin Observatory’s LSST survey. The project combined cutting-edge techniques in time-series modelling and deep learning:

1. Implemented Neural Stochastic Delay Differential Equations (Neural SDDEs) to interpolate irregularly sampled multi-band light curves onto a regular daily grid.

2. Developed a Transformer-based architecture inspired by recent research, extended with 11 metadata tokens to incorporate astrophysical context such as redshift and extinction.

3. Conducted ablation studies (stochastic vs deterministic SDDEs, with vs without metadata) and evaluated performance using weighted multi-class log loss and per-class metrics.

4. Achieved strong improvements by integrating metadata, reducing validation WMLL from 8.4 to 0.9.

This work bridges physics and data science, contributing to scalable pipelines that can help astronomers discover rare cosmic events in real-time.
