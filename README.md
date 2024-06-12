Conda is installed on bare metal.  Create an environment for Autogluon and all dependencies.
1. conda activate ag
conda install -c conda-forge mamba
mamba install -c conda-forge autogluon "pytorch==cuda"
mamba install -c conda-forge "ray-tune >=2.6.3,<2.7" "ray-default >=2.6.3,<2.7"  # install ray for faster training
conda install ipykernel
python -m ipykernel install --user --name ag --display-name "Autogluon"
#conda install pip
python -m pip install -U pip
python -m pip install -U matplotlib
pip install -U pip
pip install -U setuptools wheel



pip install autogluon



pip install ipywidgets
conda install intel-extension-for-pytorch=2.1.20 pytorch=2.1.0 -c intel -c conda-forge
