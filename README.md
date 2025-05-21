
# AI4Life Community Event Workshop 1
### Session 1: Creating, Uploading, Deploying and Containerizing BioImage Model Zoo Models

This repository provides materials for **Session 1**. It includes code and resources to help you learn how to work with the BioImage Model Zoo using Python and Jupyter notebooks.

---

## 🚀 Quick Start

The notebook can be used in Google Colab or locally, after setting up the environment.
To open the notebook in Google click here:[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/bioimage-io/AI4Life_CommunityEvent_W1S2/blob/main/loading_using_model.ipynb)
Otherwise, follow the installation steps below.


### 1. Install Conda

If you don't have Conda installed, download and install [Miniconda](https://docs.conda.io/en/latest/miniconda.html) or [Anaconda](https://www.anaconda.com/products/distribution) for your operating system.


### 2. Create and Activate the Conda Environment

Open a terminal (Anaconda Prompt on Windows or Terminal on Mac/Linux) and create a new environment called `bioimageio` with Python 3.10 by running:

```terminal
conda create --name bioimageio python=3.10
conda activate bioimageio
```

### 3. Install Required Packages

Install the main dependencies from the conda-forge channel:

```terminal
conda install -c conda-forge bioimageio.core pytorch
conda install -c conda-forge jupyterlab
conda install -c conda-forge matplotlib
```

- `bioimageio.core`: Core library for working with BioImage Model Zoo models.
- `pytorch`: Deep learning framework.
- `jupyterlab`: Interactive notebook environment.
- `matplotlib`: Plotting library.

### 4. Clone this Repository

````terminal
git clone https://github.com/bioimage-io/AI4Life_CommunityEvent_W1S2.git
cd AI4Life_CommunityEvent_W1S2
````

### 5. Launch JupyterLab

Start JupyterLab to explore and run the notebooks:

```terminal
jupyter lab
```

This will open JupyterLab in your browser. You can now open and run the notebooks provided in this repository.
