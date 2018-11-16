# ICLR-reproducibility-challenge-2019

How to use this repo:

First, go into `constrained-graph-variational-autoencoder/` and run `./install.sh`. By default this script is configured for linux.
You will need to modify one of the urls to this: https://repo.continuum.io/miniconda/Miniconda3-latest-MacOSX-x86_64.sh

Next, go back to the parent dir, and run `pip install -r requirements.txt` to get the rest of the requirements. 

You should be able to pop open my notebook and run it now. If you can't, slack me. 

The next steps here are to implement the "abstract" classes `GeneDataset` and `GeneInteractionGraph` in `gene-graph-conv/data/datasets.py` and `gene-graph-conv/data/graph_wrapper.py` respectively.
