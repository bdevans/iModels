Interactive Models for Computational Neuroscience
=================================================

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/bdevans/iModels/master?filepath=index.ipynb)

Launch the JupyterLab interface:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/bdevans/iModels/master?urlpath=lab/tree/index.ipynb)

To run the notebooks locally with JupyterLab:
```
docker run -it --rm -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes -v $(pwd):/home/jovyan/work jupyter/scipy-notebook
```
