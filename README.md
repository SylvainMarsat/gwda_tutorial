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

Launch the jupyter notebook locally:
```
jupyter-lab tutorial_1.ipynb
```

You can also click on the link at the top of the notebook if you wish to run it in Goggle Colab.

Alternatively, click on the badge below to run inside Binder:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/SylvainMarsat/gwda_tutorial/HEAD?urlpath=%2Fdoc%2Ftree%2Ftutorial_1.ipynb)
