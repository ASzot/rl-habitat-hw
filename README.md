# Homework on Reinforcement Learning in Habitat
A homework assignment in deep reinforcement learning based on the [Habitat](https://aihabitat.org) platform. 

## Run the Homework on Colab
[Run it on Colab at this link](https://colab.research.google.com/github/ASzot/rl-habitat-hw/blob/main/homework.ipynb). No installation is required for Colab.

## Run the Homework Locally

You can also run the homework locally using Jupyter Notebook. First, complete the following installation steps:

1. Requires Python >= 3.7
2. Install [Habitat Sim](https://github.com/facebookresearch/habitat-sim/tree/main): `conda install -y habitat-sim withbullet  -c conda-forge -c aihabitat-nightly`
3. Install [Habitat Lab](https://github.com/facebookresearch/habitat-lab) `pip install git+https://github.com/facebookresearch/habitat-lab`
4. Install PyTorch `pip install torch>=1.3.1`
5. Install Jupyter Notebook `conda install -c conda-forge notebook`
Work on the homework locally by filling out the cells in `homework.ipynb`.

## Troubleshooting

In Colab, if the import block below fails due to an error like "'PIL.TiffTags' has no attribute 'IFD'", then restart the Colab runtime instance and rerun this cell and the previous cell.
