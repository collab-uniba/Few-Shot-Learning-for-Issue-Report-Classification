# Few-Shot Learning for Issue Report Classification

This repository contains notebooks for training and testing the classifiers for our participation in the tool competition organized in the scope of the [2st International Workshop on Natural Language-based Software Engineering](https://nlbse2023.github.io/).

Our fine-tuned SETFIT model is available on [HuggingFace](https://huggingface.co/PeppoCola/FewShotIssueClassifier-NLBSE23).

## How to use

- `NLBSE23_1_Preprocessing.ipynb`: Runs preprocessing and saves output in order to be used from the other notebooks.
- `NLBSE23_2_RoBERTa.ipynb`: Trains and tests RoBERTa model in different settings
- `NLBSE23_3_SETFIT.ipynb`: Trains and tests SETFIT model in different settings

It is essential to run the notebook `NLBSE23_1_Preprocessing.ipynb` and store the outputs, in order to be able to run the others, as it creates and preprocess the datasets.

It is recommended to run the `RoBERTa` and `SETFIT` notebooks with a GPU.
For any problem in reproducing the experiments, feel free to open an issue or contact the authors.

## How to cite

To cite the manually annotated dataset:
```
@dataset{colavito_dataset_2023,
	title        = {Few-Shot Learning for Issue Report Classification},
	author       = {Colavito, Giuseppe and Lanubile, Filippo and Novielli, Nicole},
	year         = 2023,
	publisher    = {Zenodo},
	doi          = {10.5281/zenodo.7628150},
	url          = {https://doi.org/10.5281/zenodo.7628150}
}
```

To cite this repository
```
@software{colavito_code_2023,
	title        = {{Few-Shot Learning for Issue Report Classification}},
	author       = {Colavito, Giuseppe and Lanubile, Filippo and Novielli, Nicole},
	year         = 2023,
	url          = {https://github.com/collab-uniba/Issue-Report-Classification-NLBSE2023},
	version      = {1.0.0}
}
```

To cite the paper:
```
@inproceedings{Colavito-2023,
  title = {Few-Shot Learning for Issue Report Classification},
  booktitle = {2nd International Workshop on Natural Language-Based Software Engineering (NLBSE)},
  author = {Colavito, Giuseppe and Lanubile, Filippo and Novielli, Nicole},
  year = {2023},
}
```
