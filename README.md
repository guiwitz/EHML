[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/guiwitz/EHML/main)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/guiwitz/EHML/blob/main)

# EHML

Machine Learning course at the Business School of the Bern University of Applied Sciences

## Usage

You can run all the notebooks either via the [binder](https://mybinder.org/) service or via Google Colab using the badges at the top of this file.

In order to run the code locally, we recommend to use conda to create an environment with all the necessary dependencies. If you don't have conda installed we recommend to install [miniforge](https://github.com/conda-forge/miniforge) which is a minimal conda installer. Once installed, you can create the environment by moving to the repository folder and running the following command in the terminal:

```bash
conda env create -f binder/environment.yml
```

To use the environment, you can activate it and start jupyter lab with the following commands:

```bash
conda activate EHML2024
jupyter lab
```