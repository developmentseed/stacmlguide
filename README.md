# STAC ML Model Guide

A guide on using the Spatiotemporal Asset Catalog (STAC) Machine Learning model
extension, developed during the 2023 Gaia Pod Week STAC ML Extension hackathon.

Goals:
- [ ] Create an end-to-end tutorial on how to use the STAC ml-model extension
- [ ] Discover what limitations exist, and what can be improved

## Getting started

### Installation

To help out with development, start by cloning this [repo-url](/../../)

    git clone <repo-url>

Then, create a Python virtual environment to install the dependencies in.
We recommend [using mamba](https://mamba.readthedocs.io/en/latest/installation.html)
to initialize the virtual environment, but you can use others too.
The virtual environment should be created with Python and pip installed.

    cd stacml
    mamba create --name stacml python=3.11 pip=23.2.1

Activate the virtual environment first.

    mamba activate stacml

Install the dependencies from the `pyproject.toml` file using `pip`. This will
include several Python packages and development related dependencies like
[JupyterLab](https://github.com/jupyterlab/jupyterlab).

    pip install --editable ".[dev]"

Finally, double-check that the libraries have been installed.

    mamba list


## Resources

- STAC ML Model Extension
  - v1 spec - https://github.com/stac-extensions/ml-model/tree/v1.0.0
- Blog posts
  - https://medium.com/radiant-earth-insights/geospatial-models-now-available-in-radiant-mlhub-a41eb795d7d7
  - https://medium.com/radiant-earth-insights/discoverable-and-reusable-ml-workflows-for-earth-observation-part-1-e198507b5eaa
  - https://medium.com/radiant-earth-insights/discoverable-and-reusable-ml-workflows-for-earth-observation-part-2-ebe2b4812d5a
- Sprint format
  - Mentored sprints - https://mentored-sprints.netlify.app/organisers/01-index
