### Environment Installation
If you need to install MMDetection3D, please refer to [MMDetection Doc](https://mmdetection3d.readthedocs.io/en/latest/get_started.html) and environment.yml.

You can install the packages using `conda env create -f environment.yml` to copy my conda environment. 

Regarding the environment.yml, please make sure your GPU aligns with the cuda toolkit version. When you meet some issues about cuda, it may be because the cuda toolkit in conda environment is incomplete and you may need to setup the complete cuda in the base environment as a supplement with the same version in the conda environment. 
