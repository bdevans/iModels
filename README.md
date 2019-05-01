Interactive Models for Computational Neuroscience
=================================================

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/bdevans/iModels/master?filepath=index.ipynb)

Launch the JupyterLab interface:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/bdevans/iModels/master?urlpath=lab/tree/index.ipynb)

For further details of the binder environment, refer to [repo2docker](https://github.com/jupyter/repo2docker) [environment files](https://github.com/jupyter/repo2docker/tree/master/repo2docker/buildpacks/conda). 

To run the notebooks locally with JupyterLab:
```
docker run -it --rm -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes -v $(pwd):/home/jovyan/work jupyter/scipy-notebook
```
