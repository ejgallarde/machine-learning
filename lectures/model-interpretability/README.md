# Machine Learning 2 Model Interpretability

This repository contains codes and notebooks used in the discussion of AIM's MSDS ML2 interpretability discussion codes.

<!-- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/leolorenzoii/msds2025a-ml2/blob/main/) [![Open in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/leolorenzoii/msds2025a-ml2.git/main) -->



## Setup

To ensure that we run the codes without any dependency error, it is recommended to create an environment for this repository. To do this, first make sure that `conda` is installed in your machine (see [Conda Installation Instructions](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html)). For those who want to use `conda` in `jojie`, read the guide written in [README_jojie.md](./README_jojie.md).

### On Local Machine

After installing `conda`, create the environment for this repository using the following command:

```
conda env create -f environment.yml
```

This creates an environment named `msds2025a-ml2` and installs all the required packages with the specified version according to the `environment.yml` file specified here.

Activate this environment using the command:

```
conda activate msds2025a-ml2
```

Afterwards, launch the jupyter notebook in your machine.

```
jupyter notebook
```

Open any of the lecture notebook and ensure that the current kernel that the notebook uses is the default.

The notebooks should run without any dependency error or issue after all of this steps. 🎉

### On Jojie

After making sure that `conda` works in jojie, create the environment for this repository using the following command:

```
conda env create -f environment.yml
```

This creates a `msds2025a-ml2` on your machine and installs the required package on that environment. Additionally, since we included `ipykernel` in the dependencies, it should also install a kernel named `Python [conda env:.conda-msds2025a-ml2]`.

Use this as your kernel when running the notebooks in this repository. After you opened the lecture notebook, Select `Kernel` > `Change Kernel` > `Python [conda env:.conda-msds2025a-ml2]`.

The notebooks should run without any dependency error or issue after you set this correctly. 🎉
