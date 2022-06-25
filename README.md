# Run the Homework on Colab
Run it on Colab at [this link](). No installation is required for Colab.

# Run the Homework Locally
Installation:
1. Requires Python >= 3.7
2. Install [Habitat Sim](https://github.com/facebookresearch/habitat-sim/tree/main): `conda install -y habitat-sim withbullet  -c conda-forge -c aihabitat-nightly`
3. Install [Habitat Lab](https://github.com/facebookresearch/habitat-lab) `pip install git+https://github.com/facebookresearch/habitat-lab`
4. Install PyTorch `pip install torch>=1.3.1`
5. Install Jupyter Notebook `conda install -c conda-forge notebook`
Work on the homework in by filling out the cells in `homework.ipynb`.

# Troubleshooting

In Colab, if the import block below fails due to an error like "'PIL.TiffTags' has no attribute 'IFD'", then restart the Colab runtime instance and rerun this cell and the previous cell.
