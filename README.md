# MolBERT

This repository contains the implementation of the MolBERT, a state-of-the-art representation learning method based on
the modern language model BERT.

The details are described
in *["Molecular representation learning with language models and domain-relevant auxiliary tasks"](https://arxiv.org/abs/2011.13230)*
, presented at the Machine Learning for Molecules Workshop @ NeurIPS 2020.

Work done by Benedek Fabian, Thomas Edlich, Héléna Gaspar, Marwin Segler, Joshua Meyers, Marco Fiscato, Mohamed Ahmed

## Installation (adapted for [huggingmolecules](https://github.com/panpiort8/huggingmolecules))

Then install the package by running the following commands from the cloned directory:

```shell script
pip install transformers==3.5.1
pip install --no-deps -e .
```

## Download pretrained model (adapted for [huggingmolecules](https://github.com/panpiort8/huggingmolecules))

1. Download the pretrained model [here](https://ndownloader.figshare.com/files/25611290).
2. Extract .zip file.
3. Set ```model.pretrained_name='<extracted_path>/checkpoints/last.ckpt'```
   in ```experiments/configs/models/molbert.gin```.


