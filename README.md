# crimedatasets

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22712731.svg)](https://doi.org/10.5281/zenodo.22712731)

The `crimedatasets` package provides a curated collection of crime-related datasets from around the world, designed for data analysis, criminology research, and education in Python.

It includes extensive data on **mass shootings, hate crimes, incarceration statistics, serial killers, corruption indexes, and criminal justice metrics** spanning multiple countries including the United States, Germany, Russia, Spain, France, Sweden, Switzerland, and Scotland.

## Installation
You can install the `crimedatasets` package from PyPI:
```bash
pip install crimedatasets
```

## Usage
```python

import crimedatasets as crd

# List all available datasets

datasets = crd.list_datasets()
print(datasets)

# Load a specific dataset

df = crd.load_dataset('us_mass_shootings')
print(df.head())

```

## 📊 Some Available Datasets

### Related-Crimes Datasets

| Dataset | Description | Period |
|---------|-------------|---------|
| `berlin_crimes` | Crime in Berlin, Germany | 2012 - 2019 |
| `texas_deathrow` | Texas death row inmates | 1976 - 2018 |
| `russia_crimes` | The number of crimes in Russia | 2008-2023 |
| `arrests_national_juvenile` | Arrests of juveniles in the US by crime category | 1995-2016 |

The `crimedatasets` library is released under the **MIT License**, allowing free use for both commercial and non-commercial purposes.
