# lisabeta

Copyright (C) 2019 Sylvain Marsat, John G. Baker.
All rights reserved.

## Installation

Clone the repository:

```
git clone https://github.com/SylvainMarsat/gwda_tutorial.git
```

Create and activate a `conda` environment as
```
conda create -n gwda_tutorial -c conda-forge python=3.12
conda activate gwda_tutorial
```

Use `pip` to install dependencies, either by hand:
```
pip install numpy scipy h5py matplotlib ipython jupyterlab tqdm lalsuite gwpy
```
or using the `requirements.txt` file:
```
python -m pip install -r requirements.txt
```

We can also use `conda` to install all dependencies when creating the environment (can be slow!):
```
conda env create --name gwda_tutorial --file=environment.yml
```

Launch the jupyter notebook:
```
jupyter-lab tutorial_1.ipynb
```
