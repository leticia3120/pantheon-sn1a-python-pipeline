# A Reproducible Python Pipeline for Exploring the Pantheon Type Ia Supernova Catalog

## Overview

This repository contains a Python-based workflow developed to access, organize, and perform an exploratory analysis of the Pantheon+ compilation of Type Ia supernovae. The main objective of the project is not to derive new cosmological constraints, but to demonstrate a transparent, reproducible, and well-documented approach to handling a large and widely used astronomical catalog.

The analysis focuses on basic data preparation, descriptive statistics, and visualization of key observational quantities such as redshift, apparent magnitude, and photometric uncertainties. This repository accompanies the scientific article:

> *A Reproducible Python Pipeline for Exploring the Pantheon Type Ia Supernova Catalog*  
> (manuscript in preparation / submitted)

---

## Data

The data used in this project are drawn from the **Pantheon+ catalog**, one of the most comprehensive publicly available compilations of Type Ia supernovae. Pantheon+ combines observations from multiple surveys and provides homogenized measurements suitable for cosmological and methodological studies.

- Catalog: **Pantheon+**
- Supernova type: Type Ia
- Number of objects analyzed: **1048**
- Redshift range: approximately \( 0.01 \le z_{\mathrm{cmb}} \le 2.26 \)

The original Pantheon+ data are **not redistributed** in this repository. Users must obtain the catalog from the official source and place it in the appropriate directory, as described below.

---


---

## Requirements

The analysis was developed using **Python 3** and relies on widely adopted scientific libraries:

- `numpy`
- `pandas`
- `matplotlib`
- `astropy`

All dependencies can be installed using:

```bash
pip install numpy pandas matplotlib astropy
This repository is designed with reproducibility as a central goal. All figures and descriptive statistics presented in the accompanying paper can be reproduced directly from the scripts provided here, using the same version of the Pantheon+ catalog.

No random sampling or stochastic procedures are used, ensuring deterministic outputs given the same input data.





